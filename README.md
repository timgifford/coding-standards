You are responsible to:
=======================
- honor and respect these standards
- help your team members honor and respect these standards
- modify the standard over time

Coding Standards - Level 100
============================
- No duplication (including tests)
- Ticket # in commit message
- No commented out code
- Methods have 10 or fewer lines - Including test methods
- Methods have 3 or fewer parameters
- Classes have 7 or fewer public members (Single Responsibility)
- No method calls or logic in constructors
- No checked exceptions (Java)
- Classes are named using a noun or noun phrase
- Methods are named using a verb or verb phrase
- Variable and field names are pronounceable
- Only 1 level of inheritance

Unit Test Standards - Level 100
===============================
- No assertNotNull()
- No @Ignore tests
- 3 or fewer assertions per test method
- No mocked static methods

Coding Standards - Level 200
============================
- Only inherit from abstract or interfaces
- No name decorations (FooImpl.java)
- No getter/setters on Interfaces
- No constant interfaces
- No public constants
- Query methods don't throw exceptions
- Query methods don't change state
- Command methods change state
- Command methods throw expections when state is unable to be changed
- Factory methods over constructors

Unit Test Standards - Level 200
===============================
- Arrange, Act, Assert
- No uncovered lines
- Prefer state based testing: Prefer stubs over mocks
