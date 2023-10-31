# IT350-Course-Project

A state-of-the-art implementation of PB-DID architecture for protocol based intrustion detection.

### Datasets Used

- [UNSW-NB15](https://cloudstor.aarnet.edu.au/plus/apps/onlyoffice/s/2DhnLGDdEECo4ys?fileId=206777051)
- [Bot-IoT]( https://cloudstor.aarnet.edu.au/plus/s/umT99TnxvbpkkoE?path=%2FCSV%2FTraning%20and%20Testing%20Tets%20(5%25%20of%20the%20entier%20dataset)%2FAll%20features)

### Instructions to Run

1. Download the datasets in a folder named `datasets` in the root directory of the project. Put each dataset in a separate folder named `UNSW-NB15` and `Bot-IoT` respectively.
2. Run `pip install -r requirements.txt` to install all the dependencies.
3. Run `data_cleaning_bot.iot.ipynb` and `data_cleaning_unsw.ipynb` to clean the datasets.
4. Run `training.ipynb` to train the model.
5. Run `testing.ipynb` to test the model.