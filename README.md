If you are looking at this repo, you are already aware of mind-blowing demo (https://www.youtube.com/watch?v=D5VN56jQMWM)
of Google Duplex[1] technology at Google I/O this year. Applications built on Google Duplex technology makes automated
phone calls on behalf of user to local stores, restaurants, banks etc., to save user's time.

In the near future, Google Duplex-like technology will be used to make robo calls sound more human, more targeted/personalized;
because this is software-enabled, we will also see a rise in robo calls made to individuals, businesses and government bodies.

Some noteworthy tweets about Google Duplex/Automated Calls:
* https://twitter.com/chrismessina/status/993911460945248256
* https://twitter.com/BenedictEvans/status/994323488302186497
* https://twitter.com/levie/status/993916224105988096
* https://twitter.com/BenedictEvans/status/994292357129428992
* https://twitter.com/gaberivera/status/997172961193807872

Clearly there is a need: https://twitter.com/ProductHunt/status/997325292342460416 ;)

Inbound phone calls can be broadly classified into four categories:
1. Robo calls (aka pre-recorded calls) [https://imgur.com/a/aqMVGXJ]
2. Telemarketing calls (sales pitch from "human" salesperson) [https://en.wikipedia.org/wiki/Telemarketing]  
3. Expected calls and callbacks (calls made to return a call/action you made. ex: hotel reservation, recruiter etc.,).
4. Friends/Family/Acquaintances calls (aka call from your "social" network). 

Solutions currently available (U.S only) to reduce or identify spam calls (you may know some of them):
1. Register your phone number at donotcall.gov if you want to reduce incoming Telemarketing calls.
2. If you are on T-Mobile, your dialer shows "Scam Likely" to help you discard those spam calls.
   Precision is good but not desirable.
3. Android&iOS devices allows Truecaller app to block calls and show caller ID. Great recall and precision for caller ID
   and haven't seen truecaller app blocking my incoming spam calls (doesn't provide desirable precision of spam call detection).
4. (New) Auto call blocking on Android by Google (https://www.theverge.com/2018/4/11/17223904/google-pixel-phone-app-spam-call-voicemail-update-android)
   This is expected to have better precision and recall than Truecaller (because you know Google!).

I may have missed solutions that are currently available or being built. But, I see an opportunity in building software 
solutions for, both consumers and businesses to reduce unwanted calls and/or save time in answering "inbound"/incoming calls.
Google built a demo for automating "outbound" calls from consumer to a business.

Goal of this project is to build simple phone call assistant (solving 90% cases) which can take your phone calls and escalate
when needed after phone call captcha (thanks to Benedict Evans for the idea!).

[1] More details about Google Duplex: https://www.google.com/search?q=google+duplex
