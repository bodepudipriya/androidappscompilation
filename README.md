The compilation of Android apps can be a challengeowing to the prevailing building systems and project variations.
The paper focuses on examining 200 built Android apps with both Java and Kotlin, which are written on GitHub. Compilation
issues were grouped into five root causes dependency errors (35%), configuration errors (20%), Gradle task errors (15%),
syntax/API errors (20%), and environment issues (10%). 76 of the apps had no problems, 71 needed small fixes, 13 needed
large fixes and 40 could not be fixed because of deprecated APIs or dependencies. The workflow consisted of six stages: cloning
repositories, Gradle syncing, examining error logs, patching (e.g.upgradeVolley), fixing core problems, and recompiling with an 84
percent success rate on patchable apps such as Meme Share.Java apps had a higher percentage of configuration-related errors
(25%) than Kotlin (15%), and bigger apps (e.g.,OsmAnd, 5 hours) out of the little apps (e.g., Step Counter,10 minutes) took
longer to compile. Large Language Models(LLMs) represented a high-efficiency tool that contributed to the resolution of
issues and the discovery of trends. It has contributed to the achievement of a detailed dataset,
a graphical representation of workflow, and language-specific trends, which help Android developers.The study can give
practical answers although there are certain limitations such as the deprecated apps (e.g., Mytodolist). In the future, it might be
possible to conduct proprietary mobile application development and further integration of LLM.
