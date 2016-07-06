![feature graphic](https://raw.githubusercontent.com/klinker41/messenger/master/artwork/play%20store/feature%20graphic.png?token=AESvSsyLVWkUPx-Ugg54taWRRv62UWl7ks5XfS3PwA%3D%3D)

# Messenger

The goal of this project is to create an SMS/MMS app that has full support for all of the features
that users love, is based on material design, and supports a strong-encryption version of a tablet
messenger that sends messages through your phone.

The project will be separate from my previous messaging experience with Sliding Messaging and
EvolveSMS and will be completely rewritten from scratch for performance and consistency. The
designs themselves are loosely based off of Google Inbox and adapted as a messenger instead of
email client.

### APIs

The project will include APIs that allow any SMS app to use the online service and hook up to the
tablet app. This will be important for EvolveSMS so that support can be there and our userbase can
be larger. This app will also be very different from EvolveSMS, so the users can have their
preference on which they like more.

### Server

The server will be built so that I can host it on AWS myself, or provide a WAR file to advanced
users so that they can host it themselves and configure the app so that all messages are stored on
their own server for additional security.

Just a note, all messages and information will be stored in encrypted form at all points in the
process, except on the user's device. Strong end-to-end encryption will be rigorously enforced
and documented.

By allowing users to host themselves, I will be able to charge them a slightly greater one-time fee
($5?) instead of a monthly subscription fee ($1?) that would be the norm for this type of service.
JIRA has the same type of payment structure, as an example.

## License

    Copyright (C) 2016 Jake Klinker

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.