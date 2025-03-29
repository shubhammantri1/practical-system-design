# practical-system-design

## 🚀 Interactive System Design Challenge: Scalable Email Trigger System

Welcome to a hands-on, **interactive system design exercise**. This isn't just about building something that works — it's about **thinking through real-world problems**, step-by-step, like an engineer designing for scale.

You will **start with your own idea** for how to send emails and then be challenged through a constructive conversation with ChatGPT to evolve your system. As you go, you’ll uncover **hidden pitfalls**, consider trade-offs, and learn scalable design patterns.

### 💡 What You'll Learn

- ✅ How to design a scalable email system
- ✅ When to use (or not use) distributed locking
- ✅ How message queues (like Kafka) help in distributed systems
- ✅ Smart use of relational databases with versioning and MVCC
- ✅ Differences between cron jobs, consumer workers, and queues
- ✅ Real-world patterns for avoiding duplicate work and improving reliability

---

### 🧠 Prompt to Copy-Paste into ChatGPT

Just copy the prompt below and paste it into ChatGPT to begin:

I want to design a system that sends emails — both transactional (like order confirmations) and scheduled (like reminder or summary emails).
I'll start by sharing my initial architecture, and I’d like you to:
Challenge my design as we go
Point out scalability, reliability, or cost issues
Help me evolve the system step-by-step
Teach me relevant concepts like distributed locking, versioning, Kafka, cron jobs, database queues, etc., only as they naturally come up
Please don’t give a full answer right away — instead, let’s have a constructive, back-and-forth conversation like two engineers discussing trade-offs and exploring better solutions together.
Think of this like a real-world system design session — let’s find the best architecture through dialogue, not shortcuts.

> 💬 **Tip:** Start by describing your simplest design idea (e.g., “I’ll run a cron job on a single server”) and see how it evolves through the discussion.
