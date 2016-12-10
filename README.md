
SMS API for SMS API in python
=======================================

#### Install

    pip install git+git://github.com/atemon/python-sms-api.git


#### Usage

    from SMS import API

    sms_api = API(
        username=<Your User Name>,
        password=<Your Password>,
        sender_name=<Your Sender Name>,
    )

    rep = sms_api.send(message=<Message string>, number=<Receiver's mobile number>)

