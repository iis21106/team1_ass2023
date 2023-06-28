# team1_ass2023
Σας παραθέτουμε από κάτω τους κωδικούς και τα usernames
που θα χρειαστείτε για να κάνετε Login όταν τρέξετε το πρόγραμμα μας
από το eclipse.

EID | NAME | SURNAME | **USERNAME** | **PASSWORD** | AGE
1	| ΔΗΜΗΤΡΗΣ	| ΑΝΘΟΜΕΛΙΔΗΣ	| **gramateia**	| **gr1**	| 22
2	| ΝΙΚΟΣ	| ΚΑΡΑΚΑΣΗΣ	| **ipodoxi**	| **imech1**	| 22
3	| ΘΟΔΩΡΗΣ	| ΧΙΤΟΣ	| **epivlepon**	| **emech1**	| 21
4	| ΧΡΙΣΤΟΣ	| ΣΟΦΤΣΗΣ	| aplos	| mech1	| 22
5	| ΠΑΝΤΕΛΗΣ	| ΖΑΧΑΡΕΓΚΑΣ	| boss	| boss1	| 20
6	| ΙΑΣΩΝ	| ΠΑΠΑΔΗΜΗΤΡΙΟΥ	| engine	| mech2	| 34
7	| ΛΟΥΚΑΣ	| ΕΡΓΑΤΟΜΑΓΚΑΣ	| tires	| mech3	| 45

Επίσης όταν θα κάνετε import το Project μας στο eclipse βρείτε μετά στον φάκελο που ανεβάσαμε το αρχείο EmployeeData.db,
έπειτα πάρτε το path του και επικολλήστε το στην κλάση sqliteConnection σητν γραμμή κώδικα 14.

Connection conn = DriverManager.getConnection("jdbc:sqlite:C:\\Users\\olga\\eclipse-workspace\\tutorial1\\EmployeeData.db");

Στην παραπάνω γραμμή δηλαδή που θα βρείτε, πάρτε το δικό σας path όπου θα βρίσκεται το αρχείο αυτό και αλλάξτε το, ακολουθεί παρακάτω παράδειγμα.

Connection conn = DriverManager.getConnection("jdbc:sqlite:C:\\Users\\konstantinos\\eclipse-workspace\\tutorial1\\EmployeeData.db");

Αυτό δυστυχώς θα πρέπει να το κάνετε αναγκαστικά αν θέλετε να δείτε πώς τρέχει το πρόγραμμά μας, 
γιατί δεν αυτοματοποιήσαμε τον τρόπο με τον οποίο ο κώδικας προσαρμόζει το path με το οποίο κάνει connect το αρχείο στον κώδικα,
ώστε μετά να αντλήσει τα δεδομένα από αυτό το αρχείο ανεξάρτητα από ποιό path βρίσκεται.


