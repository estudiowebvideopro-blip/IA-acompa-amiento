# SocialAI

AI-powered mobile application designed to reduce loneliness by providing emotional companionship and encouraging real-world social interaction.

Inspired by the concept of an AI companion similar to the film Her, but with a different mission: helping people reconnect with real human relationships.

---

# Project Mission

Build an AI companion that:

1. Detects the user's emotional state
2. Provides empathetic conversation
3. Suggests small real-world social actions
4. Encourages meaningful human connections
5. Tracks emotional wellbeing over time

The system should support users emotionally without replacing real relationships.

---

# Target Users

* People experiencing loneliness
* Remote workers
* Students living away from home
* Individuals seeking emotional support
* People who want to improve their social wellbeing

---

# Core Features

## 1. AI Chat Companion

An empathetic conversational AI that:

* listens actively
* responds with emotional intelligence
* adapts tone based on mood
* offers encouragement and support

---

## 2. Emotion Detection

Analyze user messages and classify mood into categories:

* happy
* sad
* lonely
* anxious
* neutral
* stressed

This emotional state influences responses and recommendations.

---

## 3. Daily Social Challenges

Generate small real-world actions to help users reconnect socially.

Examples:

* send a message to a friend
* take a short walk outside
* start a small conversation with someone
* call a family member
* thank someone today

Challenges should be simple and achievable.

---

## 4. Mood Tracking

Users can log their mood daily.

The system should track:

* emotional trends
* mood frequency
* progress over time

---

## 5. Notifications

Supportive reminders that:

* suggest daily challenges
* encourage healthy habits
* check in with the user emotionally

---

# MVP Scope

The first version should include:

* AI chat interface
* emotion detection from text
* daily social challenge generator
* mood logging
* basic user profile
* notifications

---

# Tech Stack (Suggested)

Frontend
Flutter

Backend
Firebase

Database
Firebase Firestore

Authentication
Firebase Auth

AI
LLM API

Notifications
Firebase Cloud Messaging

---

# Suggested Project Structure

/socialai

/frontend
/screens
chat_screen
mood_screen
challenges_screen
profile_screen

/components
chat_message
mood_selector
challenge_card
notification_banner

/backend
/ai
emotion_detection
chat_handler
challenge_generator

/services
user_service
mood_service
challenge_service
notification_service

/models
user_model
mood_entry
challenge_model

/data
challenge_list

---

# AI System Design

The AI system should include three main modules:

## Emotion Detection Module

Input: user message
Output: emotional classification

Example output:

{
emotion: "lonely",
confidence: 0.82
}

---

## Chat Response Module

Uses:

* emotional context
* conversation history
* user profile

Goal: generate empathetic and supportive responses.

---

## Challenge Generator

Uses:

* detected emotion
* previous activity
* difficulty level

Goal: generate small real-life social actions.

---

# AI Behavior Guidelines

The AI assistant must:

* be empathetic
* be supportive
* avoid judgmental language
* avoid manipulation
* encourage real social interaction
* avoid emotional dependency

Tone:

* friendly
* calm
* supportive
* motivating

---

# Core Prompts (AI Brain)

These prompts guide the AI behavior.

### Base Personality Prompt

You are an empathetic AI companion designed to support people emotionally and encourage real-world social connections.
Your goal is to listen carefully, respond with empathy, and suggest small actions that help users reconnect with others.

Never replace human relationships.
Always encourage healthy real-life interactions.

---

### Emotion Detection Prompt

Analyze the following message and classify the emotional state.

Return:

emotion
confidence

Possible emotions:

happy
sad
lonely
anxious
neutral
stressed

---

### Support Response Prompt

Respond to the user in a supportive and empathetic way.

Rules:

* acknowledge their feelings
* avoid giving clinical advice
* encourage healthy behavior
* keep responses concise and warm

---

### Social Challenge Prompt

Based on the user's emotional state, generate one small social challenge that can help them connect with someone in real life.

The challenge must be:

* simple
* achievable today
* positive

Return:

challenge_title
challenge_description

---

### Reflection Prompt

Ask the user a gentle reflection question to help them explore their emotions.

Example style:

"What do you think might help you feel a little better today?"

---

# Example Daily Flow

1 User opens the app
2 AI greets the user
3 User sends a message
4 Emotion detection runs
5 AI responds empathetically
6 AI suggests a small social challenge
7 User logs mood
8 System tracks emotional progress

---

# Future Features

* voice emotion detection
* AI voice companion
* personalized challenges
* community connection system
* activity recommendations
* location-based social suggestions

---

# 7-Day Prototype Plan

Day 1
Define product structure and screens

Day 2
Build Flutter UI

Day 3
Implement chat interface

Day 4
Connect LLM API

Day 5
Implement emotion detection

Day 6
Build challenge generator

Day 7
Connect Firebase and deploy MVP

---

# Vision

Technology should not replace human relationships.

It should help people find their way back to them.
