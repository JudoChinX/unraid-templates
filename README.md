# Unraid Templates

A collection of Unraid community applications templates for apps developed by [JudoChinX](https://github.com/JudoChinX).

## How to Use

To use these templates in your Unraid server:

1.  Open your Unraid WebGUI and navigate to the **Docker** tab.
2.  Scroll to the bottom and find the **Template repositories** section.
3.  Add this repository URL: `https://github.com/JudoChinX/unraid-templates`
4.  Click **Add**.
5.  When adding a new container, select **Rangarr** from the template dropdown.

## Available Templates

### [Rangarr](https://github.com/JudoChinX/rangarr)

<p align="center">
  <img src="assets/rangarr-logo.png" />
</p>

**Rangarr** is a lightweight orchestration service that automates and staggers media searches across multiple *arr instances (Radarr, Sonarr, Lidarr). It helps keep your library complete without overwhelming your indexers or API limits.

- **Primary Configuration:** Environment Variables (Default).
- **Advanced Configuration:** Supports `config.yaml` via volume mount at `/app/config`.
- **Source Code:** [JudoChinX/rangarr](https://github.com/JudoChinX/rangarr)
- **Documentation:** [User Guide](https://github.com/JudoChinX/rangarr/blob/main/docs/user-guide.md)

---

## Support

- For issues with the **templates themselves** (e.g., incorrect paths, missing variables), please open an issue in [this repository](https://github.com/JudoChinX/unraid-templates/issues).
- For issues with the **applications** (e.g., bugs in Rangarr), please open an issue in the respective application's repository.

## Contributing

If you'd like to contribute a new template or improve an existing one, feel free to open a Pull Request!
