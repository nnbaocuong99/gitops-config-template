###### 1. `values.yaml`
```yaml
nameOverride: my-nextpay-tech
fullnameOverride:
services:
  enabled:
  global:
    imagePullSecrets:
    image:
      repository: 
    elasticApm:      
      ELASTIC_APM_ENABLED: 
  backend-project:
    enabled: 
  frontend-project:
    enabled:
  kafka-event-manager:
    enabled:
  my-nextpay-tech-chat:
    enabled:
  rethink-db:
    enabled:
  tags-api:
    enabled:
  media-server:
    enabled:
  backlog-services:
    enabled:
  fe-storage-services:
    enabled:
  redis:
    enabled:
  telegram-bot:
    enabled:
  history-service:
    enabled:
  feeds:
    enabled:
  incident:
    enabled:
  socket-noti-server:
    enabled:
  response-team-service:
    enabled:
  incident-tracking:
    enabled:
  chat-service:
    enabled:
  demo-integrated-service:
    enabled:
mariadb:
  enabled:
mongodb:
  enabled:
mongodb-replica:
  enabled:
kafka:
  enabled:
kowl:
  enabled:
```

<br>

###### 2. `output.yaml`
```yaml
---
# Source:
apiVersion:
kind:
metadata:
  name:
  labels:
    helm.sh/chart:
    app.kubernetes.io/managed-by:
    app.kubernetes.io/name:
    app.kubernetes.io/instance:
  
data:
  ELASTIC_APM_ENABLED: "true/false"
---
# Source:
apiVersion:
kind:
metadata:
  name:      
  labels:
    helm.sh/chart:
    app.kubernetes.io/managed-by:
    app.kubernetes.io/name:
    app.kubernetes.io/instance:
  
data:
  ELASTIC_APM_ENABLED: "true"
---
# Source:
apiVersion:
kind:
metadata:
  name:
  labels:
    helm.sh/chart:
    app.kubernetes.io/managed-by:
    app.kubernetes.io/name:
    app.kubernetes.io/instance:
  
data:
  ELASTIC_APM_ENABLED: "true"
---
# Source:
apiVersion:
kind:
metadata:
  name:
  labels:
    helm.sh/chart:
    app.kubernetes.io/managed-by:
    app.kubernetes.io/name:
    app.kubernetes.io/instance:
  
spec:
  replicas: 1
  revisionHistoryLimit: 1
  selector:
    matchLabels:
      app.kubernetes.io/name:
      app.kubernetes.io/instance:
  template:
    metadata:
      labels:
        app.kubernetes.io/name:
        app.kubernetes.io/instance:
    spec:
      imagePullSecrets:
        - name:
      restartPolicy:
      containers:
        - name:
          image:
          imagePullPolicy:
          envFrom:
            - configMapRef:
                name:
          volumeMounts:
          resources:
            null
      volumes:
---
# Source:
apiVersion:
kind:
metadata:
  name:
  labels:
    helm.sh/chart:
    app.kubernetes.io/managed-by:
    app.kubernetes.io/name:
    app.kubernetes.io/instance:
  
spec:
  replicas: 1
  revisionHistoryLimit: 1
  selector:
    matchLabels:
      app.kubernetes.io/name:
      app.kubernetes.io/instance:
  template:
    metadata:
      labels:
        app.kubernetes.io/name:
        app.kubernetes.io/instance:
    spec:
      imagePullSecrets:
        - name:
      restartPolicy:
      containers:
        - name:
          image:
          imagePullPolicy:
          envFrom:
            - configMapRef:
                name:
          volumeMounts:
          resources:
            null
      volumes:
---
# Source:
apiVersion
kind:
metadata:
  name:
  labels:
    helm.sh/chart:
    app.kubernetes.io/managed-by:
    app.kubernetes.io/name:
    app.kubernetes.io/instance:
  
spec:
  replicas: 1
  revisionHistoryLimit: 1
  selector:
    matchLabels:
      app.kubernetes.io/name:
      app.kubernetes.io/instance:
  template:
    metadata:
      labels:
        app.kubernetes.io/name:
        app.kubernetes.io/instance:
    spec:
      imagePullSecrets:
        - name:
      restartPolicy:
      containers:
        - name:
          image:
          imagePullPolicy:
          envFrom:
            - configMapRef:
                name:
          volumeMounts:
          resources:
            null
      volumes:
```
