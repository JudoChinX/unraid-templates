# Unraid Templates

A collection of Unraid community applications templates for apps developed by [JudoChinX](https://github.com/JudoChinX).

## How to Use

To use these templates in your Unraid server:

1.  Open your Unraid WebGUI and navigate to the **Docker** tab.
2.  Scroll to the bottom and find the **Template repositories** section.
3.  Add this repository URL: `https://github.com/JudoChinX/unraid-templates`
4.  Click **Add**.
5.  When adding a new container, select a template from the dropdown.

## Available Templates

### [Rangarr](https://github.com/JudoChinX/rangarr)

<p align="center">
  <img src="assets/rangarr-logo.png" width="256" />
</p>

**Rangarr** is a lightweight orchestration service that automates and staggers media searches across multiple *arr instances (Radarr, Sonarr, Lidarr). It helps keep your library complete without overwhelming your indexers or API limits.

- **Primary Configuration:** Environment Variables (Default).
- **Advanced Configuration:** Supports `config.yaml` via volume mount at `/app/config`.
- **Source Code:** [JudoChinX/rangarr](https://github.com/JudoChinX/rangarr)
- **Documentation:** [User Guide](https://github.com/JudoChinX/rangarr/blob/main/docs/user-guide.md)

### [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-runner)

<p align="center">
  <img src="https://about.gitlab.com/images/press/gitlab-logo-500-rgb.png" width="256" />
</p>

**GitLab Runner** is the open source agent that executes CI/CD jobs and sends results back to GitLab. This template is pre-configured for the Docker executor and auto-registers on first boot using the URL, token, and name you provide.

- **Executor:** Docker (default job image: `alpine:latest`)
- **Auto-registration:** Fills in your credentials once and the runner registers itself on first start.
- **Persistence:** Config is stored at `/mnt/user/appdata/gitlab-runner` and survives restarts.
- **Documentation:** [GitLab Runner Docs](https://docs.gitlab.com/runner/)

---

## Support

- For issues with the **templates themselves** (e.g., incorrect paths, missing variables), please open an issue in [this repository](https://github.com/JudoChinX/unraid-templates/issues).
- For issues with the **applications** (e.g., bugs in Rangarr), please open an issue in the respective application's repository.

## Contributing

If you'd like to contribute a new template or improve an existing one, feel free to open a Pull Request!
