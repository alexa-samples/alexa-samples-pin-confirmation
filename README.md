# Build an Alexa Sample Pin Confirmation skill. 🇺🇸
<img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/quiz-game/header._TTH_.png" />

This sample demonstrate how to use new [Pin Confirmation](https://developer.amazon.com/en-US/docs/alexa/custom-skills/pin-confirmation-for-alexa-skills.html) feature of Alexa skills to inform user to provide voice pin to proceed further with skill functionality.

## Skill Architecture
Each skill consists of two basic parts, a front end and a back end.
The front end is the voice interface, or VUI.
The voice interface is configured through the voice interaction model.
The back end is where the logic of your skill resides.

## Three Options for Skill Setup
There are a number of different ways for you to setup your skill, depending on your experience and what tools you have available.

 * If this is your first skill, choose the [Alexa-Hosted](https://developer.amazon.com/en-US/docs/alexa/hosted-skills/build-a-skill-end-to-end-using-an-alexa-hosted-skill.html) to get started quickly.
 * If you want to manage the backend resources in your own AWS account, you can follow the [AWS-Hosted instructions](https://developer.amazon.com/en-US/docs/alexa/custom-skills/host-a-custom-skill-as-an-aws-lambda-function.html).
 * Developers with the ASK Command Line Interface configured may follow the [ASK CLI](https://developer.amazon.com/en-US/docs/alexa/smapi/quick-start-alexa-skills-kit-command-line-interface.html).
 * If you want to host the backend code in Alexa developer account (Alexa Hosted skill) then you can directly create hosted skill by [importing Github repository](https://developer.amazon.com/en-US/docs/alexa/hosted-skills/alexa-hosted-skills-git-import.html).

---

## Setup to run this demo

**Important:** This sample code showcase how you can use Pin Confirmation feature to give option for user to provide voice pin set in Alexa account. Once user provided pin confirmation and when it successfully verified it will continue with skill functionality.

### API documentation & Resources

- [Understand Pin Confirmation](https://developer.amazon.com/en-US/docs/alexa/custom-skills/pin-confirmation-for-alexa-skills.html)
