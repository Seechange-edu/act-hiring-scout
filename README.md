# act-hiring-scout

Action Factory deploy repo for [hiring-scout](https://github.com/Seechange-edu/hiring-scout).

A Release published here (created by `hiring-scout` via `Parse-Action-Tag`) triggers
[`ci.yml`](.github/workflows/ci.yml), which checks out the `hiring-scout` source, builds the Docker
image, pushes it to ECR and deploys it over SSH.
