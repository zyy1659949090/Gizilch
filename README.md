# Gizilch

Gizilch

Description

The game of gizilch has very simple rules. First 100 grapes are labeled, in nontoxic ink, with the numbers 1 to 100. Then, with a cry of ``GIZILCH!'', the referee fires the grapes up into the air with a giant gizilcher. The two players, who each start with a score of ``1'', race to eat the falling (or, shortly thereafter, fallen) grapes and, at the same time, multiply their scores by the numbers written on the grapes they eat. After a minute, the hungry squirrels are let loose to finish the remaining grapes, and each contestant reports his score, the product of the numbers on the grapes he's eaten. The unofficial winner is the player who announces the highest score.
Inevitably, though, disputes arise, and so the official winner is not determined until the disputes are resolved. The player who claims the lower score is entitled to challenge his opponent's score. The player with the lower score is presumed to have told the truth, because if he were to lie about his score, he would surely come up with a bigger better lie. The challenge is upheld if the player with the higher score has a score that cannot be achieved with grapes not eaten by the challenging player. So, if the challenge is successful, the player claiming the lower score wins.

So, for example, if one player claims 343 points and the other claims 49, then clearly the first player is lying; the only way to score 343 is by eating grapes labeled 7 and 49, and the only way to score 49 is by eating a grape labeled 49. Since each of two scores requires eating the grape labeled 49, the one claiming 343 points is presumed to be lying.

On the other hand, if one player claims 162 points and the other claims 81, it is possible for both to be telling the truth (e.g. one eats grapes 2, 3 and 27, while the other eats grape 81), so the challenge would not be upheld.

Unfortunately, anyone who is willing to referee a game of gizilch is likely to have himself consumed so many grapes (in a liquid form) that he or she could not reasonably be expected to perform the intricate calculations that refereeing requires. Hence the need for you, sober programmer, to provide a software solution.

Input

Pairs of unequal, positive numbers, with each pair on a single line, that are claimed scores from a game of gizilch.

Output

Numbers, one to a line, that are the winning scores, assuming that the player with the lower score always challenges the outcome.

Sample Input

343 49 

3599 610 

62 36 

Sample Output

49 

610 

62 

Hint

A clarification was made at the beginning of the contest to resolve some ambiguity in the problem description noticed a couple of days before the contest. The rules for deciding the winner of a game of gizilch are, first, if both players might be telling the truth, the larger score wins. Second, if the player with the lower score cannot be telling the truth, the player with the higher score wins. Finally, if neither of the previous two conditions holds, the lower score wins.. 
