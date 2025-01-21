1. Собираем образ:

```docker build -t nifi .```

2. Запускаем контейнер

```docker run --name nifi -p 8443:8443 -v ./data:/opt/nifi/nifi-files -d nifi```

3. Заходим на https://localhost:8443 с login: **admin** pass: **ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB**
