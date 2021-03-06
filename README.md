# explain-like-im-five

## Variables
Variables are like your hands.
Someone throws you a ball. 
When your hands catches it, you store the ball in your hand.

You can now use the ball that is in your hand.

Someone can throw you a another ball.
If it's small, maybe you can hold the two balls.
If not, maybe replace the previously caught ball.

## Application Programming Interface
APIs are like the spouts of water dispensers.
If you want to get the water resource, 
you need to interact with the spout as an interface.

This protects your water resource from being accessed without limitations.

## Database
Database is like toy box.

You organize your room by placing all the toys inside the box. Otherwise, the toys will be all over the place and you won't be able to find them easily when you need them.

Database solves this issue.

## Kubernetes
https://dev.to/inidaname/explain-kubernetes-to-me-like-i-m-five-5a3f

Docker images: think of them as blueprints, for example a blueprint for creating a cow.

Docker daemon: think of it as corral for letting the cows run wild.

Docker swarm (and Kubernetes): think of it as a rancher that manages the cows.

Let's say you create many cows (docker containers) with the same blueprint (docker image) and let the cows do their thing in the corral (docker daemon).

You have all the dairy cows in one place but it's getting pretty crowded and they're eating all the stuff around them (resources) and you need to redistribute them to other areas or they will die.

You hire the rancher named Kubernetes and tell him of all the other corrals (nodes). The rancher checks each corrals capacities (resources) that they can handle. The rancher will take care of moving the cows around when the corrals are low on food to more abundant areas and the rancher will also take care of creating new cows for you if cows die for any reason.

The rancher is responsible optimizing your cattle ranch as efficient as possible and making it scale as long as you tell him of all the locations that his allowed to move the cows to. You can also tell him to only grow the ranch to a certain size or to dynamically scale larger to produce more milk based on the dairy consumption demand by the population (auto-scaling).

## Model View Controller
Source: https://softwareengineering.stackexchange.com/questions/127624/what-is-mvc-really

MVC (Model, View, Controller) is a pattern for organising code in an application to improve maintainability.

Imagine a photographer with his camera in a studio. A customer asks him to take a photo of a box.

The box is the model, the photographer is the controller and the camera is the view.

Because the box does not know about the camera or the photographer, it is completely independent. This separation allows the photographer to walk around the box and point the camera at any angle to get the shot/view that he wants.

Non-MVC architectures tend to be tightly integrated together. If the box, the controller and the camera were one-and-the-same-object then, we would have to pull apart and then re-build both the box and the camera each time we wanted to get a new view. Also, taking the photo would always be like trying to take a selfie - and that's not always very easy.

## Content Management System

## Webhooks

