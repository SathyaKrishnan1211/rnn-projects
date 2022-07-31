# RNN PROJECTS
# CHAR-RNN (Jul-29,2022)
## Description
Char-rnn aims at developing a model that can produce paragraphs similar to the corpus it was trained on.<br>
The Char-rnn model in this repository was trained on *Shakespearean text*. It is not at the level of generating Shakespearean text or any text for that
matter because the model has not regularized. Adding ```dropout=0.2``` and ```recurrent_dropout=0.2``` will make the model produce more meaningful text
but it will take hours for the model to train. You can find the trained model in **models/char_rnn.h5**.
> Snapshot of the model used to produce Shakespearean text
![Screenshot from 2022-07-31 16-15-30](https://user-images.githubusercontent.com/86184014/182022502-e3dcdca3-439f-4902-9433-8b743aca8e4b.png)

# JOHANN SEBASTIAN BACH'S MUSIC GENERATION (Jul-30,2022)
## Description
Bach music model aims at generating music similar to the music composed by *Johann Sebastian Bach*. <br>
The model successfully generates the intended music but you will find it repeating the same notes during the last 5-10 seconds, because of the nature of 
Recurrent Neural Networks. <br>
Play the chords generated using ```play_chords()``` function.<br>
The notebook has been adapted from *Aurelien Geron's* [handson-ml2 repository](https://github.com/ageron/handson-ml2)<br>
You can find the trained model in **models/bach_model.h5**.
> Snapshots of the model used to generate Bach's type music
![Screenshot from 2022-07-31 16-40-46](https://user-images.githubusercontent.com/86184014/182023507-568453c0-1c4d-49bc-b0ca-a4a2f4366d64.png)
![Screenshot from 2022-07-31 16-41-16](https://user-images.githubusercontent.com/86184014/182023514-0efa743c-ae53-48e2-b51a-1e045a50963a.png)
