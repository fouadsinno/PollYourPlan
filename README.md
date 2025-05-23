# PollYourPlan

Project Name: PollYourPlan

Application Description: Have you ever struggled setting up a plan with a group of people or friends that just doesn't end up working out? PollYourPlan helps you coordinate events with others in 3* clicks by turning the planning process into a simple and efficient poll system. Instead of endless messages in a group chat, users enter a session to create and vote on polls for an event/appointment. When everyone responds, each user can confirm the poll to automatically generate a Google Calendar invite, so that no one forgets and shows up late (or not show up at all).

Features + Tools/Technologies:
- Poll Creation: Users can create a poll with a date, location, and occasion. This uses React, HTML, and CSS.
- Multi-User: Each browser tab acts as a separate user who can create and vote on polls. This uses JavaScript. Poll synchronization across users use the BroadcastChannel API in order to send and receive poll updates in current time.
- Vote Collection and Display: Each user can vote either Yes or No and see a summary of everyone's votes. This uses React.
- Calendar Event Generation: Each user can click Confirm to generate a calendar event. This uses JavaScript and a Google Calendar Event Creation URL.
- Storing Data: Polls and votes are saved after refreshing/closing the browser. This uses JavaScript and Web Storage API.

Timeline (complete by):
- April 26: Frotend Design
- April 28: Support Multi-User Interaction
- April 30: Support Google Calendar Integration
- May 1: Ensure all features work together

We aim to complete all portions together every day in-person until the completion of the project.
