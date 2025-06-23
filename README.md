# Reproducer for [IssueTracker#407797643](https://issuetracker.google.com/issues/407797643)

```bash
gradlew :app:lintDebug
```

```raw
app/src/testFixtures/kotlin/com/example/issuetracker/Fixtures.kt:5: Error: Call requires API level 26, or core library desugaring (current min is 24): java.time.ZonedDateTime#now [NewApi]
```