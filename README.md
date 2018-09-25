# ml_ya_final
final step of specialization https://www.coursera.org/specializations/machine-learning-data-analysis

whats inside jupyter notebooks:
1 - parsing yandex.ru for reviews of mobile phones. Its long process, especially when yandex detects parsing. Output - DUMP_data.pkl
2 - normalizing data. Output - DUMP_reviews_normalized.pkl + DUMP_labels_normalized.pkl
3 - first attemp to find best estimator without tuning params
4 - gridSearch with my own 'gridSearchCustom more informative technology'.
5 - use this estimator to take part in competition at kaggle. For good result its enough to use only ngrams tuning (its because I've parsed too many reviews). 

zip contains demo (just basic web inut form developed in flask. Ugly, but worked). Demo needs files of model and vectorizer generated at step 5. 

Thats all.
Going to kaggle.
