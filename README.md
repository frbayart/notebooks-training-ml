# Create archive on MacOS

export COPYFILE_DISABLE=true
rm vm-notebooks-training.tar.gz
tar -zcvf vm-notebooks-training.tar.gz ml-training

# Upload it on S3 to be use by update-notebook
