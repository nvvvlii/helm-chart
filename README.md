# helm-chart
sonarqube helm chart

для установки чарта необходимо его добавить в Helm

helm repo add <название_чарта> https://nvvvlii.github.io/helm-chart/

Обноаить списки чартов

helm repo update

Проверка списка чартов

helm search repo <название_чарта>/sonarqube

Установка чартa

helm install sonarqube <название_чарта>/sonarqube
