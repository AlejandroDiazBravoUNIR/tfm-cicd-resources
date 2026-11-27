# tfm-cicd-resources (Autoservicio 2)

Crea los dos repositorios de una aplicación a partir de templates y configura sus variables:

- `<entorno>-<app>-infra` (desde `tfm-template-terraform-app-infra`)
- `<entorno>-<app>-app` (desde `tfm-template-app-nodejs` o `tfm-template-app-python`)

Entrada (`json_data`): `environment_name`, `app_name`, `technology` (`nodejs`|`python`), `tech_version`, `container_port`, `app_version`, `instance_type`.
