DADES DEL 1r PREPROCESSING

log_ILDS_train_X.csv
Dades d'entrenament amb transformacions, escalades i amb resampling fet.
columns = ['Age', 'TP', 'ALB', 'AR', 'DBratio', 'logTB', 'logDB', 'logAlkphos', 'logSgpt', 'logSgot', 'Female', 'Target']

log_ILDS_test_X.csv
Dades del test amb transformacions i escalades com el train.
columns = ['Age', 'TP', 'ALB', 'AR', 'DBratio', 'logTB', 'logDB', 'logAlkphos', 'logSgpt', 'logSgot', 'Female']

log_ILDS_train_X_no_resampling.csv
Dades d'entrenament amb transformacions i escalades, pero SENSE RESAMPLING.
columns = ['Age', 'TP', 'ALB', 'AR', 'DBratio', 'logTB', 'logDB', 'logAlkphos', 'logSgpt', 'logSgot', 'Female', 'Target']


DADES DEL 2n PREPROCESSING

resampled_train.csv
Dades d'entrenament amb transformacions, escalades i amb resampling fet.
['Age', 'TB', 'DB', 'Alkphos', 'Sgpt', 'Sgot', 'TP', 'ALB', 'AR', 'BilRatio', 'Female', 'Target']

scaled_test.csv
Dades del test amb transformacions i escalades com el train.
['Age', 'TB', 'DB', 'Alkphos', 'Sgpt', 'Sgot', 'TP', 'ALB', 'AR', 'BilRatio', 'Female']

resampled_train_fs.csv
Dades d'entrenament amb transformacions, escalades, resampling i feature selection fet.
['Age', 'TB', 'Alkphos', 'Sgot', 'ALB', 'AR', 'BilRatio', 'Female', 'Target']

scaled_test.csv
Dades del test amb transformacions i escalades com el train. També amb feature selection.
['Age', 'TB', 'Alkphos', 'Sgot', 'ALB', 'AR', 'BilRatio', 'Female']




