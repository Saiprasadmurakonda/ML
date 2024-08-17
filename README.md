This repository has all the ml related codes

Find the deployment at  https://placement-prediction3.onrender.com/


To pickle the file,

import pickle
**pickle_file_path = '/content/decision_tree_model.pkl'**                    # Specifying where the file should be stored
**with open(pickle_file_path, 'wb') as file:**                            # opening file in write binary format, file is not present, so one is created
    **pickle.dump(model, file)**                                          # dumping the contents of model to file
                                                                      # Now we are done with creating a pickle file, downloading it can be done from file section of google colab
