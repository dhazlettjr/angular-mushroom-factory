# mushroom-factory

Mushroom Factory
# Prerequisites
⚠️ This exercise requires that you have completed the Mushroom Mania exercise.

# Setup

These commands are a helpful quick start. You may choose to ignore them completely and create your own directory structure. If you choose to use this recommendation, just copy the commands below and paste. It doesn't matter what directory you are currently in.

mkdir -p ~/workspace/exercises/modern-framework/mushroom-factory && cd $_

# Requirements

You are going to modify your Mushroom Mania application to use a factory to retrieve the mushroom data instead of retrieving it directly in your controller.

Create a new factory for your Angular application. Make sure your factory returns something.
Inject the factory dependency into your controller.
Invoke the appropriate function that your factory exposes to get the mushroom data.
When the method is successful, take the results and put them into $scope.mushrooms variable in your controller that is bound to the partial.
