# How to setup Tensorflow in GCP (MUJEFA)

1. Go to Marketplace 
2. Search for "ml" and search for (MUJEFA - Python AI & Machine Learning Kit)
3. Customize the VM (following were the options I picked.)
	- 2-CPU option
	- 30GB boot disk
4. Change password for ubuntu user
	- sudo passwd ubuntu
	- > and set password to something you remember

5. Go to SSH and intall TF and whatever you want
     - > which condo (for me it was /home/anaconda/condabin/conda)
     - > sudo /home/anaconda/condabin/conda install tensorflow
     - > sudo /home/anaconda/condabin/conda install -c anaconda pillow

6. Go to a incognito window and issue 
	- http://external-ip

Walah you will see the Jupiter notebook with tensorflow, scikitlearn, matplotlib, etc.