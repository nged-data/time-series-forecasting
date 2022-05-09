<!-- ABOUT THE PROJECT -->
## About The Project

This Jupyter notebook provides an example of what you can do using data published on WPD's connected data portal. This specific Lab will walk you through extracting time series data through API calls and creating a simple forecast using Python. Please note this forecasting example is purely for demonstration purposes only.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Jupyter](https://jupyter.org/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* [Anaconda](https://www.anaconda.com/products/individual)


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/wpd-data/time-series-forecasting.git
   ```
2. Creating a new environment is not strictly necessary, but given that installing other ML packages from different channels may cause dependency conflicts (as mentioned in the note above), it can be good practice to install the stack in a clean environment starting fresh.

    The following commands create a new environment with the name ts_env, configures it to install packages always from conda-forge, and installs lightgbm in it:
   ```
   conda create -n geo_env
   conda activate geo_env
   conda config --env --add channels conda-forge
   conda config --env --set channel_priority strict
   conda install python=3 lightgbm
   ```
3. Open Jupyter Notebook and run

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this notebook in conjunction with WPD's connected data portal to explore and forecast the vast array of time series datasets available.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

N/A

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the WPD Open Data License. For more information see [here](https://www.westernpower.co.uk/open-data-licence)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Louie Sellwood - wpddata@westernpower.co.uk

Project Link: [https://github.com/wpd-data/time-series-forecasting/](https://github.com/wpd-data/time-series-forecasting/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Liam McSweeney
* George Kiely


<p align="right">(<a href="#top">back to top</a>)</p>
