# flutter-bitbucket-pipeline
Bitbucke Pipeline to generatek apk and send to slack channel.

### Requirements to send apk to slack
>SLACK_TOKEN - token to authorize slack apis.
>SLACK_CHANNEL - Id of channel.
### Flutter Image
- Latest Image used in this repository.
>image: cirrusci/flutter:latest

 
- Or specify the verison on which your project is working.
>image: cirrusci/flutter:3.0.5

### Command used to build the apk
- build apk specific flavour.
> flutter build apk --flavor dev -t lib/main_dev.dart

- or replace the pipeline command with the one you ar using.
> flutter build apk


