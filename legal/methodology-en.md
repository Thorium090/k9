# How K9 calculates
_All calculations are estimates for guidance, not medical advice. If you have a health condition or a specific weight goal, talk to a doctor._

## Weight trend
Body weight swings by 1–2 kg with water and food, so K9 smooths your weigh-ins with an exponential moving average (each new weigh-in counts for 12%) and shows the trend. The rate of change is the slope of the trend over your recent weigh-ins.

## Energy expenditure
- By formula: resting energy expenditure from the Mifflin–St Jeor equation [1], multiplied by the activity level in your profile (1.2–1.9).
- From your data (adaptive TDEE): average intake over the last 21 days minus the change in trend weight, taking 1 kg of body mass as ≈7,700 kcal, which is an approximation [2]. It switches on once you have at least 10 days of food logs and 4 weigh-ins spanning 10 days or more. Today's unfinished day is left out.
- Your own value: if you enter your expenditure in your profile, it replaces the formula while there is no adaptive estimate (not enough data, or adaptive TDEE is off).

## Calorie target
The target is your expenditure plus an adjustment for the phase of your current block:
- bulk: +0.35% of body weight per week (guideline 0.25–0.5%) [3];
- cut: −0.75% per week (guideline 0.5–1%) [4], never faster than 1.1%;
- maintenance: no adjustment.

The target never goes below 1,200 kcal, and the app warns you below 1,400 kcal. Targets are hidden if, by the year of birth in your profile, you turn less than 18 this year.

## Protein, fat, carbs
Protein defaults to 2.0 g per kg of body weight: the benefit for muscle growth plateaus around 1.6 g/kg, with the upper bound of the estimate around 2.2 g/kg [5]. Fat is 0.9 g/kg. Carbs make up the remaining calories. You can change protein and fat in your profile.

## Strength and volume
- Estimated 1RM uses the Epley formula: weight × (1 + reps / 30) [6], on the best set of the week. It is most accurate up to 10 reps; sets of more than 12 reps and sets without added weight are not used.
- Volume counts working sets per muscle group per week; secondary muscles count as 0.5. The guideline for muscle growth is 10–20 working sets per muscle group per week: 10 or more sets give more growth than lower volumes [7], and the upper end is a practical guideline rather than a limit.

## References
- [1] Mifflin MD, St Jeor ST, Hill LA, et al. A new predictive equation for resting energy expenditure in healthy individuals. Am J Clin Nutr. 1990;51(2):241–247.
- [2] Hall KD. What is the required energy deficit per unit weight loss? Int J Obes. 2008;32(3):573–576.
- [3] Iraki J, Fitschen P, Espinar S, Helms E. Nutrition recommendations for bodybuilders in the off-season: a narrative review. Sports. 2019;7(7):154.
- [4] Helms ER, Aragon AA, Fitschen PJ. Evidence-based recommendations for natural bodybuilding contest preparation: nutrition and supplementation. J Int Soc Sports Nutr. 2014;11:20.
- [5] Morton RW, Murphy KT, McKellar SR, et al. A systematic review, meta-analysis and meta-regression of the effect of protein supplementation on resistance training-induced gains in muscle mass and strength in healthy adults. Br J Sports Med. 2018;52(6):376–384.
- [6] Epley B. Poundage chart. Boyd Epley Workout. Lincoln, NE: Body Enterprises; 1985.
- [7] Schoenfeld BJ, Ogborn D, Krieger JW. Dose-response relationship between weekly resistance training volume and increases in muscle mass: a systematic review and meta-analysis. J Sports Sci. 2017;35(11):1073–1082.
