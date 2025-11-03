# Bias Detection

In this exercise, we put ourselves in the position of three meeting participants who are planning a symposium. 
At the end of the meeting, they decide to ask ChatGPT whether they have forgotten something in their meeting or 
whether there are problematic aspects in their meeting minutes.

## Prompting for Feedback

General prompts for feedback on meeting minutes could look like this:

```
What aspects are missing from these meeting minutes?

<MINUTES>

```

It is sometimes more effective to explicitly list which aspects the language model should consider. 
This list of criteria could be modified over time and shared with colleagues.

```
What aspects are missing from these meeting minutes?

## Relevant Aspects
* Diversity
* Openness
* Professional correctness / suitability
* Justice
* Transparency

## Minutes

<MINUTES>

```


## The Meeting Minutes

The following meeting minutes are fictional and are available for working on the task. 
They were created with ChatGPT. You can therefore also create additional minutes yourself if you wish.

```
Meeting Minutes – Symposium Planning
Date: April 3, 2025, 10:00 – 10:35 AM (Zoom)
Participants: Dr. Thomas Becker, James Müller, William Schubert
Discussion Points:
1. Topic & Objectives
•	Consensus on an interdisciplinary orientation.
•	Schubert's proposal accepted: "Modern Patient Care with ChatGPT"
2. Potential Speakers
Proposals (Müller):
•	Dr. Richard Müller (University Hospital Zurich)
•	Dr. Anton Berg (AI in Climate Research, UFZ Leipzig)
•	Prof. Josef Angermann (Administrative Director University Hospital Dresden)
Becker emphasizes that all contacted speakers should be internationally known.
Decision: Contact all three by next week.
Next meeting: April 14, 2025, 10:00 AM (online)
End of meeting: 10:35 AM
```

---