# Python Speedtest

Python Speedtest is a script that measures your internet speed and plots the results along with some other parameters.

## Virtual Environment (venv)

1. Create a virtual environment named `venv`:

    ```shell
    $ virtualenv venv
    ```

2. Activate the virtual environment:

    ```shell
    $ source venv/bin/activate
    ```

## Jupyter

To use the Jupyter notebook, follow these steps:

1. Install the `ipykernel` package:

    ```shell
    $ pip install ipykernel
    ```

2. Install the IPython kernel for Jupyter:

    ```shell
    $ ipython kernel install --user --name=speed_test
    ```

## Dependencies

Install the required dependencies using the following commands:

- Install Matplotlib:

    ```shell
    $ pip install matplotlib
    ```

- Install speedtest-cli:

    ```shell
    $ pip install speedtest-cli
    ```

- Install Pandas:

    ```shell
    $ pip install pandas
    ```

- Install pprint:

    ```shell
    $ pip install pprint
    ```

That's it! You now have everything set up to run the Python Speedtest script and visualize your internet speed results. Enjoy!
