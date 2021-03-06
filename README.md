# Pluggable-FSM-AI
This implementation of a finite state machine uses Unity's scriptable objects to break each state down into an Action, Decision, and state to transition to. This allows a designer to "plug" different scriptable objects together to form different behaviors for enemy AI.

<br>For example, a patrolling state could have the "action" of moving back and forth between two waypoints, a "decisition" to transition out of this state if the player comes within agro range, and a "State to transition to" could be an attacking or chasing state. These attacking or chasing states would also have their own Actions, Decisions, and states to transition to.

<br>Creating different states for your enemy AI which are comprised of different Actions, Decisions, and 'States to transition to' can create different behaviors. 
