# SpeechToOpenActivity
In this video the activity will be open with speech , When you speech activity the next activity will be open

    It will do it through RecognizerIntent.
    You do not require any internet connection to use the voice to text service. 
    It will work in Offline mode.

#### Condtion

    if (mVoiceInputTv.getText().toString().equals("activity"))
         {
           Intent intent = new Intent(getApplicationContext(),NewActivity.class);
           startActivity(intent);
         }

<img src="Screenshot_2021-03-06-13-26-38-846_com.google.android.googlequicksearchbox.jpg" width="200"> &nbsp; <img src="Screenshot_2021-03-06-13-24-54-134_com.asw.androidspeechtotext.jpg" width="200">
