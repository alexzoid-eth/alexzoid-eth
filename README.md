# Formal Verification Services

I am a formal verification specialist ([x.com/alexzoid](https://x.com/alexzoid)) with deep expertise in Certora, currently ranked 🏆 #1 on the Certora Community Contest [leaderboard](https://certora.com/leaderboard) with multiple top placements in competitive contests.

## Track Record

- **Portfolio**: [github.com/alexzoid-eth/public-fv-reports](https://github.com/alexzoid-eth/public-fv-reports) - Public specifications and reports
- **Methodology**: [alexzoid.com](https://alexzoid.com) - Detailed insights into my verification approach

## Verification Approach

My verification approach follows a systematic methodology. After initial project setup, I develop a comprehensive list of properties in plain English, then categorize them using official Certora's [property approach](https://github.com/Certora/Tutorials/blob/master/06.Lesson_ThinkingProperties/Categorizing_Properties.pdf) as a foundation: valid state, variable transition, state transition, and high-level properties. Additional property types such as "Isolation", "EIP Compliance", etc, are incorporated as needed.

### Property Categories

**Valid State Properties**  
Define the permissible values for system variables (e.g., "Total sum of user balances MUST equal total shares for each position type"). These foundational properties serve as proven constraints for state transition and high-level properties.

**Variable Transition Properties**  
Verify how variables change and maintain validity throughout the system lifecycle. While some variables must change monotonically, others may vary freely (e.g., "lastBatchId MUST increment by exactly 1").

**State Transition Properties**  
Ensure correctness when transitioning between valid states (e.g., "Pool shares and tokens change in the same direction").

**High-Level Properties**  
Capture system behavior from the user perspective, covering end-to-end functionality (e.g., "After a swap, the number of limit order shares held by LPs MUST remain unchanged").

## Validation & Delivery

Upon completion, I validate property quality through both automated and manual mutation testing, delivering comprehensive specifications with a detailed final report.
