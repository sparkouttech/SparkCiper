# SparkCiper

composer require sparkciper/ciper

Ciper::encrypt('RANDOM_KEY','RANDOM_IV','STRING_TO_ENCODE');

The above method return encrypted string 

Ciper::decrypt('RANDOM_KEY','RANDOM_IV','ENCODED_STRING');

The above method returns original string from encoded string
