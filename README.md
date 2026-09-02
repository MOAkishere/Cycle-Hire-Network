# Cycle-Hire-Network
The whole project is one question: can you predict how many bikes will be at a station in 30 minutes better by looking at its neighbours than by looking at its own past?

To answer that you need data. TfL only tells you what's happening right now. It doesn't keep a history for you. So if you want to know what a station looked like at 3pm last Tuesday, the only way is to have asked at 3pm last Tuesday and written it down.

That's why the first job is a robot that asks TfL "how many bikes at every station?" every fifteen minutes, forever, and saves each answer. It runs on Google's servers so it keeps going when your laptop is closed. Every day it runs, you have more data. Every day it doesn't, that day is gone permanently.