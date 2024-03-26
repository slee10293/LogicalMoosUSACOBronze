# LogicalMoosUSACOBronze

Farmer John has a boolean statement that is N keywords long (1≤N<2⋅105, N odd). Only 𝚝𝚛𝚞𝚎 or 𝚏𝚊𝚕𝚜𝚎
 appear in odd positions, while only 𝚊𝚗𝚍 and 𝚘𝚛 appear in even positions.

SAMPLE INPUT:
5 7
false and true or true
1 1 false
1 3 true
1 5 false
3 3 true
3 3 false
5 5 false
5 5 true


First Query → [1,1]
True and true or true 
→ True or True 
→ True 
False and true or true 
→ False or true
→ True 
Cannot be false; therefore N 
