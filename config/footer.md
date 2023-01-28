
---

## 📬 Contributing

Built or discovered a new workcell app? I'd love to have it in this list! You can 
either:

- [Open an issue](https://github.com/weanalyze/best-of-workcell/issues/new/choose) with 
a link to the app/repo
- Add the app yourself by [editing projects.yaml directly online](https://github.com/weanalyze/best-of-workcell/edit/main/projects.yaml) 
(no forking required). Just add the following information at the end of this file:

    ```yaml
    - name: App Name  # required; keep it short
      homepage: link/to/deployment  # required; if not deployed, give repo link
      image: link/to/gif/png/jpg  # optional; if not given, will take screenshot of homepage
      github_id: owner/repo  # optional
      category: one of the categories below  # required
      show: True # optional; If True, the project will always be shown even when the project would be actual hidden
    ```

    For `category`, choose one from below (e.g. `ml`) or leave empty if you are not 
    sure:
 
    ```yaml
    - category: demo
      title: 🎈 Official Demos
    - category: sci-tech
      title: 🧬 Science & Technology
    - category: bi
      title: 📈 Business Intelligence
    - category: fin
      title: 💰 Finance
    - category: ml
      title: 🤖 General Machine Learning
    - category: nlp
      title: 📚 Natural Language Processing
    - category: cv
      title: 👁️ Computer Vision
    - category: audio
      title: 🎵 Audio
    - category: non-ml
      title: 🚀 Non-ML Apps
    - category: extension
      title: 🪐 Extensions & Components
    ```

    *Note: The new app will not show up in the gallery directly. I first need to 
    re-generate the README.md file from projects.yaml after your changes are merged.*

- If you want to suggest any other change, feel free to [open an issue](https://github.com/weanalyze/best-of-workcell/issues/new/choose) 
as well :)

<br>

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
