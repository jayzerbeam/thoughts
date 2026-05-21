# The New Tech Debt

At one point in my career I happened to work with a talented engineer who "moved fast and broke things". He would dive straight in and start building, rapidly prototype and integrate new features, wasting little time with forethought. Management would salivate at the velocity.

There was of course a trade-off to such speed. Like a boat through water, the faster the speed the greater the wake, and this wake was pure tech debt. The features came fast but would often require refactoring - sometimes substantial - to reach an acceptable state of maintainability, extension, and/or scaling. Of course by the time it came to clean up the mess, he would have moved on to the next thing.

LLMs have redefined how we develop software, and incidentally, redefined tech debt.

Tech debt in traditional software development is over complicated code that incurred high cognitive load, when what was built was inflexible and resistant to change.

LLMs care not for traditional tech debt. They will breeze through headache-inducing spaghetti with little issue... so long as it fits in the context window. Rigid code is nothing when shifting a hundred, a thousand, a hundred-thousand LoC is no longer tedious... so long as you don't care about token cost.

However, LLMs will still produce tech debt - albeit with a different odour than that of human written code - unless guided with skilled oversight. LoC will explode, meaning disappears from tests, patterns and conventions become ignored. All problems with humans, too, but humans will actually learn. I swear, Sometimes I feel like models have been tuned to produce code that will incur greater token cost so it generates more revenue the next run through a model.

Little review or oversight of generated code means no human technical subject matter expert, the SME is now some agent. Agents can do some really neat things but they still hallucinate, ignore instructions, wander off, and produce slop. Not exactly what you want during a P0 incident. Sure, an agent may succeed, or not. What happens when no agent or human understands what's going on? Well, no company has ever suffered consequences from firing that one guy who knew how important stuff worked, right?

Don't get me wrong, I love me some coding LLMs, I can't imagine not using them for day-to-day work anymore. But tech debt hasn't magically disappeared because of them, it now just has a different smell.
