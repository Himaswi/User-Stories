```mermaid
flowchart TD

    USER[User] -->|asks| QUESTION[Question]
    USER -->|answers| ANSWER[Answer]
    QUESTION -->|has| ANSWER
    USER -->|comments| COMMENT[Comment]
    QUESTION -->|has| COMMENT
    ANSWER -->|has| COMMENT
    USER -->|votes| VOTE[Vote]
    VOTE -->|applies to| ANSWER
```
