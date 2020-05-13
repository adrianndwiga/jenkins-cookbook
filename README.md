# jenkins-cookbook

Running jenkins in a docker controller 

## 1. Setup

setup.sh

## 2. Run

run-docker-jenkins.sh

## 3. Installing plugins

### 3.1 Installing plugins

#### 3.1.1 Template

```sh
java -jar jenkins-cli.jar -s http://localhost:8080/ install-plugin SOURCE ... [-deploy] [-name VAL] [-restart]
```

#### 3.1.2 Example

### 3.2. Get list of installed plugins

#### 3.2.1 Template

```sh
java -jar jenkins-cli.jar -s http://<IP Adddress> list-plugins — username <Username> — password <Password>
```

#### 3.2.2 Example

## 4. Create pipeline

### 4.1 Jenkins CLI

```sh

```

## References
https://www.jenkins.io/user-handbook.pdf
