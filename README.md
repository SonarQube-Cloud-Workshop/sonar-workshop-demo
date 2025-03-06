## 1. import and clone repo to local

git clone https://{user_name}:{token}@github.com/{org_name}/workshop-project.git

## 2. manual scan

- Example

```bash
mvn clean install -DskipTests=true sonar:sonar -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=ab83837cf00d600234cca44e3d728504c1aade95
```

- 2025.03.06

```bash
mvn clean install -DskipTests=true sonar:sonar -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=18d669d673d759f5adde1d2269a3d509157109e3
```
