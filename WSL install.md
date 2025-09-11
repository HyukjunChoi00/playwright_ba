### WSL 설치 (Ubuntu)

### 2025.09 기준

- powershell prompt(anaconda powershell prompt)를 실행하여 아래 코드 입력  
```
wsl --install
```

- 시작 메뉴에서 Ubuntu 검색 후 실행 (터미널 화면이 나오고, 계정 이름 및 비밀번호를 설정할 수 있습니다. 비밀번호 입력할 때는 텍스트가 원래 안 보이니까 참고해주세요)


```
wget https://repo.anaconda.com/archive/Anaconda3-2025.06-0-Linux-x86_64.sh
```

```
bash Anaconda3-2025.06-0-Linux-x86_64.sh
```

터미널 재시작

```
pip install jupyter
```

```
jupyter notebook
```

- jupyter notebook 코드를 실행해서 나오는 링크에 접속해 jupyter를 window가 아닌 linux 환경에서 실행할 수 있습니다.

http://localhost:  링크를 ctrl 클릭

- playwright_linux.ipynb 파일 참고하여 이후 설치 과정 진행
- 기존에 컴퓨터에 깔려있던 jupyter는 꺼두고 수행해주시는 것을 권장드립니다.
