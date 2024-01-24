# Quick start

1. `$ git clone https://github.com/mage-ai/platform_template.git`
1. In the current directory (the parent directory of `platform_template`), start Mage:
    ```
    docker run \
    -e ENABLE_PROJECT_PLATFORM=1 \
    -it \
    -p 6789:6789 \
    -v $(pwd):/home/src \
    mageai/mageai:latest /app/run_app.sh mage start platform template
    ```
