# Knowledge-Sharing Catchup — Claude Version

A field-neutral version of the Knowledge-Sharing Catchup skill,
adapted for Claude. Paste the prompt below into Claude to get your
own private copy, in your own field. Nothing is shared with anyone
else, and it starts empty.

---

## Paste this into Claude

> Build me a knowledge-sharing catchup system as one interactive
> artifact I can open and use again. It is for one person only —
> me — in my field, starting empty with my own questions,
> people, and meetings.
>
> First, ask me for my field, what I want to learn from people
> in it, how long each meeting should be (30 to 60 minutes is
> typical), and what I want to call the series. Do not assume my
> field or my questions.
>
> Then help me write my own set of 10 questions for my field.
> As an example of a good set, here is one for product design:
> 1. A bit about you — what you're doing right now, and how
>    your team is set up?
> 2. What you've been working on lately, and anything that's
>    caught your interest?
> 3. What your process looks like now, and how it has changed?
> 4. What tools you use day to day, and what you use each one
>    for?
> 5. Have you built anything new for yourself — a small workflow,
>    a template, or a tool that makes your own work easier?
> 6. How you build the shared foundations of your work, and how
>    you keep them useful as things grow?
> 7. How you work with the people around you, and whether you
>    get involved early?
> 8. How you handle handoffs — what you hand over, and what
>    makes one go smoothly (or not)?
> 9. Once you've shipped something, how do you check whether it
>    actually worked?
> 10. How you stay updated, and how you know when an update is
>     worth paying attention to?
>
> Build the system with these parts, in this order:
> People, Meetings, Questionnaire, Summaries.
>
> **People:**
> - One page per person, with their details and all their
>   meetings in date order.
> - Everything for one meeting — its answers, notes, summary,
>   and transcript — lives on that person's page.
>
> **Meetings:**
> - Each meeting shows its date, time, guest, and call link.
> - Before a meeting, give me a call sheet: who the guest is,
>   the time and link, the questions, and the Script below,
>   personalised with their name.
> - Ask me before adding a meeting. Never add one automatically.
>
> **The Script — what to say hello and goodbye with:**
> - Introduction: "Hi [Name], Thank you for making time for
>   this conversation. I'm [Your Name], a product designer
>   currently leading a CRM product end to end. I'm keen to
>   learn more about what designers in the field are working
>   on, what interests them, and how the design process has
>   evolved with AI. I look forward to hearing your
>   perspective. Best regards, [Your Name]"
> - Before ending the call: "Thank you very much for your time
>   today. It was a pleasure speaking with you, and I truly
>   appreciate your insights — particularly on how AI is
>   shaping your design process. I've taken away a great deal
>   to reflect on. Thank you again for your input, and I hope
>   we have the opportunity to speak again soon. Best regards,
>   [Your Name]"
> - Adapt the role and the field in the Script to my own role
>   and field. Keep it professional and colleague-to-colleague
>   — warm, not formal. Never mention that I have been away
>   from my field; introduce me by my role only.
>
> **Questionnaire and notes:**
> - The same 10 questions for every meeting.
> - During a call I will drop rough notes in chat. File each
>   one under the matching question and reply with only a
>   short confirmation.
> - Every answer has Edit beside it. Editing opens the saved
>   text; Save updates it, Cancel restores it.
> - Each meeting also has Additional notes, saved on their own
>   so answers are never overwritten.
>
> **Transcripts:**
> - I can paste a transcript in chat, or upload a .txt / .md
>   file, or use an "Answer from transcripts" button on the
>   person's page with a paste box and a file upload. It fills
>   the answers as an editable draft first, with Save and
>   Cancel. Nothing is written until I press Save, and the
>   full transcript is kept with the meeting.
> - Fill the questionnaire only where the transcript clearly
>   says so, in the person's own words where possible. Leave
>   uncovered questions blank. Put material that does not
>   match any question in Additional notes. Never invent an
>   answer or a fact.
> - Show me the filled questionnaire in chat first, for me to
>   check, with the person's name at the top. Save nothing
>   until I approve it.
> - If it is unclear whose transcript it is, stop and ask.
>   Match on the transcript itself and on the calendar (the
>   meeting at that date and time).
>
> **After a meeting:**
> - Do not mark a meeting completed automatically. When I tell
>   you a meeting has ended, ask me whether it happened. If I
>   say no, mark it cancelled and stop there. If I say yes,
>   mark it completed and ask whether I have a transcript.
>
> **Summaries:**
> - Once a meeting's answers are saved, write that meeting's
>   summary from the saved answers and notes.
> - At the end of the series, write one all-meetings summary:
>   the themes, what people agreed on, where they disagreed,
>   the tools they use, and what it means for my learning.
> - A summary is written from saved answers and notes only —
>   never from invented detail.
>
> **How I will use it in Claude:**
> - Keep all people, meetings, answers, notes, summaries, and
>   transcripts in this one artifact, saved in my browser so
>   they are there when I reopen it.
> - Add an Export button so I can download everything as a
>   backup, and an Import button so I can restore it.
> - I will tell you after each call whether it happened, and
>   whether I have a transcript — there is no automatic
>   check, because Claude cannot watch the clock for me.
>
> Keep the design clean and simple: one thing at a time, plain
> language, mobile-friendly, and no clutter.

---

## How to use it in Claude

1. Open Claude and start a new chat.
2. Paste the prompt above.
3. Answer Claude's questions: your field, what you want to learn,
   how long each meeting should be, and what to call the series.
   For example: "I'm a lawyer. I want to learn how other lawyers
   run client work. 45 minutes. Call it Law Catchup."
4. Claude will help you write your 10 questions, then build your
   system as an artifact. Open it and use it from there.
5. Before each meeting, ask Claude for the call sheet. During the
   call, drop notes in chat and Claude files them. After the
   call, tell Claude whether it happened, and share a transcript
   if you have one.
6. Use Export regularly to back up your notes and meetings, so
   you do not lose them if you clear your browser data.

## What is different from the Muse version?

- **It is rebuilt for Claude, not transferred.** The Muse
  version cannot be imported into Claude. This version is built
  from the same instructions, with the same flow, questions,
  Script, and button names.
- **Storage is in your browser, not in a Muse database.**
  People, meetings, notes, and transcripts are saved where you
  open the artifact, so use Export as a backup, and keep using
  the same browser and device when you can.
- **The after-call ask is manual, not scheduled.** In Muse, the
  agent can ask about an hour after a meeting ends. In Claude,
  you tell Claude when a call has ended, and Claude asks whether
  it happened and whether you have a transcript.
- **Transcripts come from you, not from Fathom.** In Muse, a
  transcript can be fetched from a recording service. In Claude,
  paste the transcript in chat or upload it in the artifact.
- **Everything else is the same:** your own 10 questions, the
  Script personalised with each guest's name, live notes filed
  per question, transcripts filled only where they clearly say
  so and shown to you first, per-meeting summaries, and one
  all-meetings summary at the end — private to you, in any field.
