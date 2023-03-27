# Class 31 notes - Context API

## Choosing the State Structure

**Summarize the five principles for structuring state.**
1. Group related state into one.
2. Avoid contradictions.
3. Avoid redundant state.
4. Avoid duplication.
5. Avoid deeply nested state.

## Passing State Deeply with Context

**What problem do Contexts aim to solve?**
Context lets a parent component provide data to the entire tree below it. 

**What is one technique to try before useContext?**
passing props

**What hook complements useContext for complex applications?**
reducer
