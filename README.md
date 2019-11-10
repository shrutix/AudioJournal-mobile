# AudioJournal-mobile
Audio Journal lets you record or upload audio, and then automatically transcribes them, extracts keywords, and creates a summary.

## How can people use Audio Journal?

* Doctors have to listen to patients, take notes, and think about possible treatments all at the same time. No wonder it feels like doctors don't listen to you! Audio Journal helps doctors keep track of diagnoses, symptoms, and more, so they see the details of each individual plus big picture trends in disease outbreaks, with public health implications.

* Students consume lots of audio—lectures, videos, even reviewing aloud to yourself. Audio Journal saves you from re-watching hours of lectures, or clicking through dozens of pages to find which lecture mentioned a certain topic.

* Keeping an audio diary can help you record milestones in life and improve your mental health, but it's hard to figure out which files are about what. By automatically detecting topics and summarizing the content, Audio Journal lets you focus on what matters.

## How did we build this?

* We built a mobile app that records audio, uses speech recognition to transcribe it, and sends that data to our backend.
* We built an API that puts the audio and transcript in a database, and extracts keywords and a summary using natural language processing APIs.
We built a dashboard that lets users browse all their audio files, transcripts, keywords, summaries, timestamps, location, and more!
* To show an example of Audio Journal in action, we built a map of disease diagnoses from hypothetical audio recordings of patients' medical appointments. This can help public health stakeholders prevent, predict, and respond to disease outbreaks.