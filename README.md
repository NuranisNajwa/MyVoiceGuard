# MyVoiceGuard
MyVoiceGuard is a web app that scores uploaded audio for “real” vs “fake/cloned” speech. A Netlify UI calls a Flask API on Render (Docker + ffmpeg). A sklearn model (MFCC features, model.pkl) returns a label using a ≥90% = REAL rule, aligned with train_model.py.
