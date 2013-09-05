---
layout: post
title:  "Fight against eye tracking SDK"
date:   2013-09-05 23:23:23
categories: reserach
---
It's a hard day. We spent 5 hours for fighting against eye tracking SDK in windows. We went through all source code and document, finally, we found what's the problem was. The gaze SDK does not support for Tobii REX device. So, we gave up trying to execute the python code of analytics SDK. For integrating oscpack library into C++ project, I spent much effort to setup the environment parameters and link the external libraries. 

During 3-hour fight, I sucessfully completed the environment setting and sent a osc message to another client. The only fly in the ointment was the error of wrong argument type. It's a struct data from eye tracking SDK, I need to convert them into normal data type such as float, int, or string. I believe that we can solve those problems tomorrow. Go fighting!!!!!


`@janetyc :-)`

