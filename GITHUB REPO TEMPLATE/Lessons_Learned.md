# 🛠️ Lessons Learned: [Project Name]

A record of what went wrong, why, and how it shaped the next version.  
This is where future-you will thank present-you.

Use this document to explain:
- Why decisions were made.
- What failed and how it was fixed.
- What you'd do differently if you were starting over.

Be honest. Include surprises, setbacks, and discoveries.

---

## 🔍 1. Early Mistakes / Misunderstandings

Document flawed assumptions, knowledge gaps, and oversights that led to failure or wasted time.

Examples:
- Mistake: Assumed stepper motors wouldn't skip steps under load.  
  Lesson: Always calculate torque margins and verify through testing.

- Mistake: Believed cheap IMUs would "just work" without filtering.  
  Lesson: Sensor data is noisy; plan for signal conditioning.

- Mistake: [Describe the mistake]  
  Lesson Learned: [What you realized or changed]

---

## 🔄 2. Design Changes Due to Failures
Capture the reason behind any hardware or software revisions. Document what failed, why, and how you fixed it

| Issue Description        | Root Cause                  | Solution / Change                  |
|--------------------------|-----------------------------|-------------------------------------|
| PCB browned under load   | Trace width too small       | Increased trace width               |
| IMU gave inconsistent data | Poor placement, vibration  | Moved to center of mass             |
| Robot tipped on start    | Control loop too slow       | Improved ISR timing                 |
| [Describe issue]         | [What caused it]            | [How you resolved it]               |

---

## 🚧 3. Debugging Challenges

Record difficult bugs and how they were solved. What issues were tricky, what solved them. List major debugging pains, what didn’t work, and what eventually solved it.

Each challenge should follow this structure:

- [Describe the challenge]
- [Dead ends, false leads, or methods that didn’t help]
- [The final working solution]

Examples:
- UART was unstable; root cause was shared clock domain mismatch.
- PID instability traced to using raw noisy sensor data.

---

## 🔧 4. Improvements in Process / Workflow

What you’d do differently next time—not just technical, but planning and workflow (planning, testing or execution.)

Examples:
- Start with a simple mechanical prototype before finalizing CAD.
- Validate power margins before committing to board layout.
- Define file naming and commit standards early.

- [Process improvement observation]
- [Process improvement observation]

---

## 🚀 5. Key Takeaways for Future Projects

Summarize broader lessons that apply to other builds.
Broader lessons that will guide you on future hardware/software builds.

Examples:
- Always design for testability and accessible debugging.
- Favor robust, proven solutions over clever tricks.
- Power, thermal, and mechanical limits matter as much as software.

- [General principle or practice you learned]
