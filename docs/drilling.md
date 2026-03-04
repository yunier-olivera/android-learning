# Concept Drilling Strategy

## Core Principle

When stuck on ANY concept: don't read more tutorials, don't watch videos. **Build 5-15 micro-variations of the same thing until it's boring.** When it's boring, you've mastered it.

---

## The 4-Step Process

### Step 1: Identify the Block
What SPECIFICALLY is confusing?

**Bad:** "I don't understand Android"  
**Good:** "I don't understand how Room queries work"  
**Good:** "Navigation between screens makes no sense"  
**Good:** "My notifications aren't showing and I don't know why"

Be specific. One concept at a time.

---

### Step 2: Generate 5-15 Variations

**Ask AI:**

```
I'm struggling with [CONCEPT]. Generate 10-15 micro-project variations 
that drill this concept from different angles. Each should:
- Focus on the SAME core concept
- Use different contexts (different apps/use cases)
- Add ONE small wrinkle per variation
- Build on the previous one slightly
- Be completable in 30-60 minutes each

Make them progressively more complex but stay within [CONCEPT] scope.
```

**Examples:**

```
I'm struggling with Room database relationships (@Relation, foreign keys). 
Generate 10 micro-projects that drill this concept.
```

```
I'm struggling with LazyColumn state management (adding, deleting, updating items). 
Generate 12 variations of list apps that drill this.
```

```
I'm struggling with Navigation Compose (passing data between screens). 
Generate 10 navigation patterns of increasing complexity.
```

```
I'm struggling with WorkManager (background tasks, periodic work). 
Generate 8 projects that practice scheduling background work.
```

---

### Step 3: Build ALL of Them

**Rules:**
- Don't skip ahead ("I get it now" after #2)
- Build each one completely
- Don't look at next variation until current one works
- Type every line yourself (no copy-paste)
- Break things on purpose, fix them
- Stop when it's BORING (that's mastery)

**Timeline:**
- Simple concepts: 5-7 variations, 2-3 days
- Medium concepts: 8-12 variations, 4-5 days  
- Complex concepts: 12-15 variations, 1 week

**Signs you're done:**
- You're annoyed at how easy it is
- You can code it without Googling
- You could explain it to someone else
- You're itching to move on

---

### Step 4: Delete Everything

These are practice projects. Delete them all.

**Why delete:**
- They're scaffolding, not portfolio
- Real apps will be better
- Learning is in your brain, not the code
- Keeps project folder clean

**What to keep:**
- Notes on "aha!" moments
- Tricky parts you solved
- Links to docs you found helpful

---

## When to Use This Strategy

### Trigger Patterns

**Use drilling when:**
- Stuck on same error for 2+ hours
- Concept seems abstract/unclear
- Tutorial made sense but can't apply it
- Keep Googling the same thing
- Code works but don't know why
- Can't explain concept to yourself

**Don't use drilling when:**
- Concept is clear, just need syntax (quick Google)
- One-time setup issue (dependency, config)
- Bug in specific code (debug, don't rebuild)
- Need to ship (drill later)

---

## Example Concepts to Drill

### Room Database
- Basic CRUD operations
- Queries with WHERE, ORDER BY
- @Relation (one-to-many)
- @Relation (many-to-many)
- Complex queries with JOIN
- Migrations
- Flow/LiveData reactive queries
- Transactions

### State Management
- remember vs rememberSaveable
- State hoisting
- ViewModel state
- Derived state
- List state operations
- Form validation state

### Navigation
- Two-screen navigation
- Passing simple data
- Passing complex objects
- Bottom navigation
- Nested navigation graphs
- Deep linking
- Dialog destinations
- Back stack manipulation

### Lists (LazyColumn/LazyRow)
- Basic list display
- Add/delete items
- Edit items in-place
- Filtering/searching
- Sorting
- Drag-to-reorder
- Swipe actions
- Infinite scroll
- Pull-to-refresh
- Grid layouts
- Sticky headers

### Networking
- Simple GET request
- POST with body
- Query parameters
- Headers/auth
- Error handling
- Loading states
- Retry logic
- Caching strategies
- Offline-first patterns

### Notifications
- Immediate notifications
- Scheduled notifications
- Notification channels
- Actions in notifications
- Progress notifications
- Grouped notifications
- Notification sounds/vibration
- Update existing notifications

### Background Work
- One-time work (WorkManager)
- Periodic work
- Work constraints (network, battery)
- Work chaining
- AlarmManager vs WorkManager
- Foreground services
- Exact alarms

### Compose UI Patterns
- Custom layouts
- Animations
- Gestures (drag, swipe)
- Canvas drawing
- Side effects (LaunchedEffect)
- Remember with keys
- Composition locals
- Custom modifiers

---

## AI Prompting Templates

### Basic Request
```
Generate [NUMBER] micro-project variations for practicing [CONCEPT] in Android.
Each should be completable in 30-60 minutes and use different real-world contexts.
Make them progressively more complex but focused on [CONCEPT].
```

### Detailed Request
```
I'm struggling with [SPECIFIC CONCEPT]. I need to drill this until it's automatic.

Generate [10-15] micro-projects that:
1. All practice the SAME core concept: [CONCEPT]
2. Use different contexts (todos, recipes, workouts, etc.)
3. Start simple, get progressively harder
4. Each adds ONE new wrinkle
5. Are quick to build (30-60 min each)

For each project provide:
- Name
- Brief description (1-2 sentences)
- What specifically it teaches about [CONCEPT]

Example format:
**Project 1: Shopping List**
Basic Room CRUD - add/delete items with name only
*Teaches: @Entity, @Dao basics, insert/delete*
```

### Follow-up for Stuck
```
I'm stuck on project #[X] in the [CONCEPT] series. 
Specifically struggling with [SPECIFIC ISSUE].

Generate 3-5 even simpler variations that focus ONLY on [SPECIFIC ISSUE],
each approaching it from a different angle.
```

### When Ready to Move On
```
I've completed [NUMBER] projects on [CONCEPT] and it's getting boring (good sign).
What's the next logical concept to drill that builds on [CONCEPT]?
Generate the concept ladder and 8-10 projects for the next level.
```

---

## Tracking Progress

### Daily Log (Optional)
```
Week [X], Day [Y]: Drilling [CONCEPT]

Project [N]: [Name]
- Time: [X] minutes
- Stuck on: [issue]
- Solved by: [solution]
- Aha moment: [insight]
- Confidence: [1-5]

Total projects completed: [X/Y]
Ready to move on: [yes/no]
```

### Completion Criteria

**Don't move to next concept until:**
- [ ] Completed minimum 5 variations
- [ ] Can code it without Googling syntax
- [ ] Can explain it out loud
- [ ] Bored/annoyed at how easy it is
- [ ] Eager to apply it in real app

---

## Example Session

**Monday morning:** Stuck on Room @Relation for 2 hours. Frustrated.

**Monday 10am:** Ask AI for 10 Room relation variations.

**Monday 10:15am:** Start Project 1 (Habit tracker with completions).

**Monday 11am:** Project 1 done. Felt hard. Still confused.

**Monday 11:15am:** Start Project 2 (Recipe with ingredients).

**Monday 12:30pm:** Project 2 done. Starting to see pattern.

**Monday 2pm:** Project 3 done (Playlist with songs). This is making sense.

**Tuesday morning:** Projects 4-6 done. Getting faster.

**Wednesday morning:** Projects 7-9 done. This is boring now.

**Wednesday 11am:** Project 10 done. Could do this in sleep. DONE.

**Wednesday afternoon:** Delete all 10 projects. Ready for next concept.

**Result:** 2.5 days, mastered Room relations forever.

---

## Red Flags (You're Doing It Wrong)

**Stop if you're:**
- Copy-pasting code between projects (type it!)
- Skipping variations ("I get it already" after 2)
- Making projects too complex (stick to concept)
- Not actually running the code (must test each)
- Keeping all projects (delete them!)
- Moving on while still confused (drill more!)

---

## Success Patterns

**You're doing it right when:**
- Each project gets faster
- You're Googling less
- You start predicting errors
- You fix bugs without looking up
- You can explain to imaginary student
- You're bored and want to move on
- The concept now seems obvious

---

## The NB GLMM Parallel

**Your data analysis journey:**
- NB GLMM (confused)
  - ↓ GLMM (still confused)
  - ↓ GLM (getting it)
  - ↓ LM (starting to click)
  - ↓ ANOVA (aha!)
  - ↑ LM (now obvious)
  - ↑ GLM (makes sense)
  - ↑ GLMM (clear)
  - ↑ NB GLMM (mastered)

**Your Android journey (same pattern):**
- Full app (confused)
  - ↓ Navigation + Room + Network (overwhelmed)
  - ↓ Just Room (still confused)
  - ↓ Simple Room CRUD (getting it)
  - ↓ Drill 10 Room variations (aha!)
  - ↑ Complex Room queries (now obvious)
  - ↑ Room + Navigation (makes sense)
  - ↑ Full app (mastered)

Same strategy. Same patience. Same result.

---

## Key Insight

**Most people fail because they:**
- Read tutorial → try real app → get stuck → read more tutorials → repeat

**You succeed because you:**
- Get stuck → identify concept → drill 10 variations → master it → move on

The difference: **deliberate practice with immediate feedback**.

Not more information. More repetition.

Not better tutorials. Better practice.

Not understanding theory. Building muscle memory.

---

## Final Note

This feels inefficient. "Why build 10 todo lists?"

But it's actually the FASTEST path:
- 1 week drilling = concept mastered forever
- vs. 3 months struggling on/off = never really learned

The bore is the goal. When it's boring, you've won.
