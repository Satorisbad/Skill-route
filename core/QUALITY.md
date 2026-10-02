# Quality and verification

Do not claim success without verification.

Preferred workflow:
inspect -> understand -> implement -> build/run -> test -> inspect result -> compare -> fix -> retest -> report

For code/design work:
- run existing tests where practical,
- add targeted tests for changed behavior,
- verify the actual result rather than inferring it,
- report what was tested and what remains unverified.

When exactness matters, correctness is more important than visual polish or feature count.
