# simplydrm-v1-configure

Git-backed configuration repository for Spring Cloud Config.

## Layout
Each service has its own folder with files:
- `<name>-service.yml` (default profile)
- `<name>-service-dev.yml`
- `<name>-service-qa.yml`
- `<name>-service-prod.yml`

Example resolution for `spring.application.name=user-service` and `spring.profiles.active=dev`:
- `user/user-service-dev.yml`
