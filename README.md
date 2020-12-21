# Meals Calendar Infrastructure
Simple calorie tracking CRUD web app with social login

## Technologies
* Kubernetes
* Ingress
* Docker
* Jenkins

## Usage

### Configurations needed
* Deployment
* Service
* Ingress Controller
* Ingress
* ConfigMap for [tgcoding/meals-calendar-backend](https://github.com/tgcoding/meals-calendar-backend)
* Secret for docker repo user/pass

### ConfigMap Environment Variables
* `DB_URL`: Full database connection url (including `jdbc:sqlserver://`)
* `DB_USER`: Database username
* `DB_PASS`: Database password
* `GOOGLE_CLIENT_ID`: Google OAuth 2.0 Client ID
* `GOOGLE_CLIENT_SECRET`: Google OAuth 2.0 Client Secret
* `TOKEN_SECRET`: JWT Secret

### Companion Projects
* [tgcoding/meals-calendar-ui](https://github.com/tgcoding/meals-calendar-ui): React frontend
* [tgcoding/meals-calendar-backend](https://github.com/tgcoding/meals-calendar-backend): Spring Boot backend
