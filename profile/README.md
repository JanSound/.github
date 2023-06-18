# 10Seconds 🎙️

## How to run (react-native)
### 1. git clone
```bash
git clone https://github.com/JanSound/10Seconds-frontend.git
```

### 2. install react-native-cli in global
```bash
npm install -g react-native-cli
```

### 3. instsall node modules
```bash
npm install
```

### 4. install ios dependency
```bash
cd ios
pod install
```

### 5. run emulator
```bash
npm run ios
```

## How to run (server)
### 1. git clone 
Repo: https://github.com/JanSound/10Seconds-backend-go
```
git clone https://github.com/JanSound/10Seconds-backend-go.git
```

### 2. run by Go
```shell
cd src
go install
go run main.go
```

### 3. run in Docker
```shell
docker build -t tenseconds-go .
docker run -d -p 8001:8001 tenseconds-go

# 이후에는 아래의 스크립트 실행을 통해 배포
sh scripts/rebuild_and_restart.sh
```
