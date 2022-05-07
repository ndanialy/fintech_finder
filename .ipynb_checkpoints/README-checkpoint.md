# fintech_finder

A rudimentary streamlit application that uses blockchain transactions to hire Fintech professionals

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [streamlit](https://docs.streamlit.io/library/get-started?msclkid=90f80fcec86511ec86357acd59d2b43a) for the user interface.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [haslib](https://docs.python.org/3/library/hashlib.html?msclkid=a7a6860bc86511ecb96f394a27d3543c) for hasing the blocks.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html?msclkid=cee58621c86511ec8a5abaadba28fd0f) for classifying the data.

* [datetime](https://docs.python.org/3/library/datetime.html?msclkid=e396ee15c86511ec88b1f63bc0d726fc) for assigning dates in realtime.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install streamlit
```
Ganache will also need to be installed.

---

## Usage

In order to use the application, run the comman '''streamlit run fintech_finder.py''' in the terminal, this opens the homepage of the app including a list of available professionals:

![homepage](https://user-images.githubusercontent.com/96391748/167239675-db8ac9b0-6724-435f-8ccc-668676d10d02.PNG)

In the sidebar of the application you have the option to select one of the professionals and select an amount of time to hire them for:

![hiring candidates](https://user-images.githubusercontent.com/96391748/167239710-363054e8-8245-4bad-a516-957698db6613.PNG)

Finally, the user clicks the "Send Transaction" button at the bottom of the sidebar which sends the transaction to the ethereum account:

![send transaction](https://user-images.githubusercontent.com/96391748/167239833-60b14b4c-faa4-417a-bb42-26782f65a648.PNG)

The cost of the transaction is taken out of your account which is reflected in the ganache software under the accounts tab:

![ganache account](https://user-images.githubusercontent.com/96391748/167239898-b768cb88-c11b-43b2-a95b-cf25a642c1f6.PNG)

The transactions are saved on the ganache application under the "Transactions" tab:

![ganache transactions](https://user-images.githubusercontent.com/96391748/167239862-77f2e455-8d73-4032-b97a-ba1e23639156.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE