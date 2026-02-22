Can Your Breath Reveal Your Metabolism? This Helsinki Startup Says Yes — Here’s How ![Photo by Olga K.](/assets/Publications/breathome.jpg "Photo by Olga K.")

# Can Your Breath Reveal Your Metabolism? This Helsinki Startup Says Yes — Here’s How

*Published on 2025-10-30 10:00*

Today we’re speaking with Javier Jorganes Villanueva and Elena Blinova the founders of Vire (**Breathome Analytics**), a healthtech startup currently based at Maria 01 in Helsinki. The team recently pivoted and is now deeply engaged in market and user research, refining both their messaging and partner pitch. While the updated materials are still in progress, this conversation offers a chance to explore the founders’ backgrounds, the origins of their idea, and their vision for Vire’s role in shaping health and wellness-driven innovation.

### I. Origins & CEO’s Background / Team Formation

Olga K.: Javier, could you share a bit about your backgrounds, what inspired you to create this startup project, and how the company’s name came about?

Javier Jorganes Villanueva: We started this project because we saw **breath as an untapped source of health data.** My own motivation came from personal health struggles — realizing how invisible metabolism still is, and how powerful it could be if we made it visible in daily life. Originally, we called it Vire (suggested by ChatGPT), but we discovered the trademark was already taken. That forced us to rebrand, and we’re now moving forward as **Breathome Analytics,** which better reflects our vision of building a “home” for breath-based data.

**Olga:** Was there a point where you questioned your own domain knowledge (e.g. in breath chemistry, clinical validation) — and how did you patch that gap?

**Javier:** Yes, in the beginning I questioned the domain knowledge. Then I realized that we have to cook our own meal, even if we do not know how. I guess that is part of the process. Fortunately for us, now there are incredible tools that make all kind of knowledge available for every one. Also breath analysis is quite a new thing which is under research, so it would be difficult to find specialist in the field any way. An specialist on the field like to write scientific papers about it, which we can read afterward. I think those researches rarely try to make business or a product from their knowledge.I patch that gap researching by my own and using AI.

**Olga:** You’re CEO & Business Strategy lead. What is your deepest weakness (in tech or science) that the co-founders or early hires must decisively cover?

**Javier:** I’m a generalist. I enjoy the big picture and strategy, but I don’t enjoy solving very specific technical puzzles, like debugging code. That’s why Elena leads the technical side — she thrives on those problems. **My role is to keep us moving on vision, partners, and strategy**.

**Olga:**  What is a formative story or experience (pre-Vire) that still informs your leadership style today?

**Javier:** I’ve learned to invest in communication. It’s tempting to keep frustrations bottled up, but then the “pressure cooker” explodes later. So I try to open the lid regularly — be transparent with my co-founder, share doubts, and align. That honesty keeps the team healthy, especially in early-stage chaos.

![Photo by Olga K.](/assets/Publications/breathome1.jpg)

### II. The Idea & Innovation of Vire (Breathome Analytics)

**Olga:** Breath analysis fields often struggle with confounders (diet, ambient air, hydration). What’s your approach to separating physiologic signal from noise reliably? 

Elena Blinova Our approach has three layers:

**Controlled data collection:** We start with standardized protocols — fasting vs. post-meal, known meal composition, and repeat sampling — so we know the expected physiologic direction of change. Ambient air baselines are also captured before each breath to subtract background noise.

**Sensor-level corrections:** Temperature, humidity, and pressure are continuously recorded. These environmental signals are used to normalize raw MOx outputs and account for hydration or ambient variability.

**Modeling strategy:** Instead of relying on absolute values, we focus on intra-individual changes (e.g., post-meal vs. fasting baselines). This helps filter out cross-person confounders and emphasizes true physiologic responses.

**Olga:** In your AI modeling, how do you validate when a “feature” is biologically meaningful vs. a spurious correlate? 

**Elena**: We combine data-driven validation with biological grounding:

**Correlation with biomarkers:** We calibrate model outputs against independent ground-truth measures such as blood ketones and glucose, which lets us confirm whether a learned feature tracks a relevant metabolic pathway.

**Cross-condition testing:** Features are tested across controlled conditions (fasted 12h, 16h, 24h, post-meal). If a feature consistently shifts in the expected biological direction, we consider it meaningful.

**Robustness checks:** We apply permutation tests and cross-validation to identify features that persist across participants, sessions, and devices, filtering out spurious correlations. Let's break it down: **Cross-validation** → We split the data into training and test sets multiple times. If a feature keeps showing up as important no matter how we split the data, it’s more likely to be meaningful rather than just luck.

**Permutation tests** → We shuffle the labels (e.g., “fasted” vs. “post-meal”) randomly and re-run the model. If the feature disappears when labels are random, but is strong when labels are correct, it means the feature truly relates to physiology and not noise.

Across participants, sessions, devices → If the same feature appears not just in one person or one device, but across different users, times, and hardware, then it’s more trustworthy.

**Expert review:** Features that emerge are interpreted together with domain experts (gas sensing and physiology) to ensure biological plausibility before being integrated into user-facing metrics.

**Olga:** Clinicians are notoriously conservative. What is your plan to get early clinical “champions” (versus just wellness adopters) onboard?

**Javier:** That’s exactly why we pivoted to wellness first. Going after clinicians too early would slow us down with regulation and adoption hurdles. The plan is: prove value in wellness, gather real-world data, then later explore clinical validation when the economics and evidence align.

**Olga:** How do you see the line between wellness-tool vs regulated diagnosis blurring (or not) in Vire’s (**Breathome Analytics**) roadmap?

**Javier:** There’s a clear line. For us, **wellness is the training ground**. We can learn, iterate, and get to market faster without regulatory drag. Diagnostics will always be a separate track — but one we might return to when the time is right.

**Olga:** Do you expect to license your data / model to third parties (e.g. pharma, research institutions)? If yes, how do you guard privacy / model drift?

**Javier:** Maybe in the future, but it’s not our focus today. If I spend energy thinking about licensing deals now, I I lose focus on the real challenge: building a reliable product people actually use.

![Photo by Olga K.](/assets/Publications/breathome2.jpg)

### III. Finland, the Medical Innovation Ecosystem & Strategic Positioning

Olga: Being based in Helsinki gives access to certain grants, labs, clinical networks — but also distance from large markets (US, Asia). How are you balancing those pros and cons? Javier: Right now, we don’t need to solve global market access. The Finnish ecosystem gives us grants, labs, and credibility to build the product. Once we prove traction here, we can think about scaling. Olga: In your view, what’s missing (or lagging) in the Finnish healthtech / medtech ecosystem that you believe Vire (Breathome Analytics) either needs to accept or try to fill? Javier: I’m too early to critique the ecosystem. For now, we accept it as it is and focus on what we can control: product and soon partners. Olga: How do you foresee “reimbursement” evolving for breath diagnostics — as diagnostic devices, as health monitoring tools, or as consumer wellness? Javier: I believe all models will coexist: diagnostics, monitoring, consumer wellness. Breath is such a rich signal that it will spread across all of them as the tech matures. Olga: In Finland we have strong public health care, academic hospitals, and government innovation arms. Which institutional or clinical partners are you courting (or leveraging) locally? Javier: We’re not engaging clinical partners at this stage. Our current priority is getting the product right. Once we’ve proven the core technology, then we’ll evaluate the right partnerships and business model — whether that’s with wellness platforms, sport apps, or eventually clinical institutions.

![Photo by Olga K.](/assets/Publications/breathome3.jpg)