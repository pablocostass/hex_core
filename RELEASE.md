# Release process

1. Bump version in `src/hex_core.app.src`

2. Ensure CHANGELOG is updated and add current date

3. Commit changes above with title "Release vVERSION"

4. Publish docs: `rebar3 hex docs`

5. Push master and the new tag

6. Create GitHub release

7. Publish package: `rebar3 hex publish`

8. Publish docs: `rebar3 hex docs`