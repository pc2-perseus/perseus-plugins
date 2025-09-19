# PERSEUS plugins

> ⚠️ PERSEUS is currently in beta. The number of plugins is therefore limited at the moment and will be increased in the future.

PERSEUS is a compute project management software for scientific HPC centers. It allows you to
* professionalize your workflows
* deploy center-wide automation
* fully customize workflow items (states), (micro)services and reports

To learn more about PERSEUS, please visit the following:
* [PERSEUS main repository](https://github.com/pc2-perseus/perseus)
* [Documentation](https://perseus-project.pc2.uni-paderborn.de/docs/)
* [Live demo](https://perseus-project.pc2.uni-paderborn.de/preview/)

## Plugins

To install a plugin, please browse the available plugins here in this repository.

If you found a plugin that you want to use, simply download it and move it to the corresponding mount directory:

- state plugins to the custom-states directory
- services and reports to the custom-services directory

If you are unsure where these directories are located or how they appear in the first place, check out our documentation
about the [docker-compose file used](https://perseus-project.pc2.uni-paderborn.de/installation/use_docker-compose/#prerequisites).

After moving the plugin to the corresponding directory, you need to restart PERSEUS core:

```shell

docker restart perseus-core # if you use docker
podman restart perseus-core # if you use podman

```

If you have any questions, please [visit our documentation](https://perseus-project.pc2.uni-paderborn.de/docs/) or [contact us](https://perseus-project.pc2.uni-paderborn.de/contact/).

## License

This project is licensed under the terms of the **MIT License**.
See the [LICENSE](./LICENSE) file for details.
