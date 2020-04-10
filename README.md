# Generate Seinfeld scripts using RNN-LSTM and Word Embeddings
Generate tv scripts or dialogs using Seinfeld scripts database using AI


## Project Overview
This network is going to generate Seinfeld TV scripts using RNNs. it will be using a Seinfeld dataset of scripts from 9 seasons. The Neural Network will generate a new, "fake" TV script.

[![Sample Output](https://aws.revistavanityfair.es/prod/designs/v1/assets/785x589/181790.jpg)](https://aws.revistavanityfair.es/prod/designs/v1/assets/785x589/181790.jpg)



# Datasets

* Download the [Seinfeld Chronicles](https://www.kaggle.com/thec03u5/seinfeld-chronicles)

* Number of unique words: **46367**
* Number of lines: **109233**
* Average number of words in each line: **5.544240293684143**


## RNN ARCH


    RNN(
      (embedding): Embedding(21388, 256)
      (lstm): LSTM(256, 256, num_layers=2, batch_first=True, dropout=0.5)
      (fc): Linear(in_features=256, out_features=21388, bias=True)
    )


-----

​	Loss has been achieved up to **3.27** with **10 epochs** 



## Generated Output

    jerry: and kramer comes over to her office, and they were a very important person.

    jerry:(pointing to his notebook) oh, you know, you know, i just want to see her naked, and i just got the same thing, you know, i have no control of that.

    newman: well, i just wanted to go.

    kramer: well, i'm not going to be the one who deserved a lot of humor.

    jerry: well, you know, it's not fair.

    jerry:(to george) you know, i'm sorry, i'm sorry. i was wondering, i was going to the movies.

    jerry: oh, yeah.

    george:(to jerry) hey, hey.

    elaine: hey, hey! you see what? i was trying to get it out.

    george: oh, yeah.

    kramer: well, i'm sorry about the show.

    elaine: yeah.

    jerry: well, i don't think so, i don't think i have to talk, i was in the hospital.

    jerry: oh, no.(they both leave) what are you doing?

    jerry: no, you don't know.

    elaine: oh, yeah.

    kramer: hey, what are you talking about?

    jerry: yeah, well, you know, you can get it out of it, i just wanted to talk.

    jerry: i don't know. you know, the only part of the world series. i mean i'm going.

    george: you know what?

    kramer: yeah, i just got the car out of the building...

    george:(still in his head) i don't know what the hell are they gonna be able to say something?

    jerry: no.

    george:(to george) i was just curious.

    jerry:(to elaine) oh, no, i can't believe it!(to kramer) you know what? you were in the bathroom.



