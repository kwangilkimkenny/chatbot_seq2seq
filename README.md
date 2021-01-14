# chatbot_seq2seq


1.가상환경 설치

conda  create -n venv_chatbot python=3.5 anaconda

2.가상환경 실행
conda activate venv_chatbot

3.가상환경 종료
conda deactivate



Tensorfow 1.0.0 설치
Pip install tensorflow==1.0.0


학습용 coupus download

This corpus contains a large metadata-rich collection of fictional conversations extracted from raw movie scripts:

220,579 conversational exchanges between 10,292 pairs of movie characters

involves 9,035 characters from 617 movies

in total 304,713 utterances

movie metadata included:

genres

release year

IMDB rating

number of IMDB votes

IMDB rating

character metadata included:

gender (for 3,774 characters)

position on movie credits (3,321 characters)

see README.txt (included) for details

https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html




# 참고: https://blog.ggaman.com/1000

# Windows 10 64bit에서 Tensorflow(텐서플로우) 설치 하기

# Anaconda 설치

# Anaconda 에서 tensorflow를 위한 가상환경 만들기

# Windows 10에서 동작하는 tensorflow는 python 3.5를 지원하므로 python은 3.5로 지정해서 python 환경을 먼저 만들어야 한다. 
# 이 환경 이름을 tf 라고하자. 

# conda create --name tf python=3.5 라는 명령을 이용하면 python 3.5를 기반으로 하는 tf라는 환경을 만들 수 있다.

# activate tf 실행하여 가상환경 작동

# >> conda install -c conda-forge tensorflow=1.0.0 



1.가상환경 설치
conda create -n venv_chatbot python=3.5 anaconda
2.가상환경 실행 conda activate venv_chatbot
3.가상환경 종료 conda deactivate
Tensorfow 1.0.0 설치 Pip install tensorflow==1.0.0
