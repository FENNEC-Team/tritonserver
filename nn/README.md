# NN

Detection pipeline:
- License detection with [YoloV5](https://github.com/ultralytics/yolov5)
- License alignment with [STN](https://pytorch.org/tutorials//intermediate/spatial_transformer_tutorial.html)

# Tests

1. Install and activate virtual environment

    ```bash
    poetry install --with=dev
    poetry shell
    ```

2. Run tests

    ```bash
    pytest ./tests -vv --disable-warnings
    ```
