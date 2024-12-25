Sets είναι λίστες χωρίς διπλές καταχωρήσεις. Ας υποθέσουμε ότι θέλετε να συλλέξετε μια λίστα από λέξεις που χρησιμοποιούνται σε μια παράγραφο:

Αυτό θα εκτυπώσει μια λίστα που περιέχει "my", "name", "is", "Eric", και τέλος "and". Εφόσον οι υπόλοιπες λέξεις της πρότασης είναι ήδη στο σύνολο, δεν προστίθενται δύο φορές.

Τα sets είναι ένα ισχυρό εργαλείο στην Python αφού έχουν τη δυνατότητα να υπολογίζουν διαφορές και τομές μεταξύ άλλων συνόλων. Για παράδειγμα, ας πούμε ότι έχετε μια λίστα συμμετεχόντων στα γεγονότα A και B:

Για να βρείτε ποια μέλη παρακολούθησαν και τα δύο γεγονότα, μπορείτε να χρησιμοποιήσετε τη μέθοδο "intersection":

Για να βρείτε ποια μέλη παρακολούθησαν μόνο ένα από τα γεγονότα, χρησιμοποιήστε τη μέθοδο "symmetric_difference":

Για να βρείτε ποια μέλη παρακολούθησαν μόνο ένα γεγονός και όχι το άλλο, χρησιμοποιήστε τη μέθοδο "difference":

Για να λάβετε μια λίστα όλων των συμμετεχόντων, χρησιμοποιήστε τη μέθοδο "union":

Στην παρακάτω άσκηση, χρησιμοποιήστε τις δεδομένες λίστες για να εκτυπώσετε ένα σύνολο που περιέχει όλους τους συμμετέχοντες από το γεγονός A που δεν παρακολούθησαν το γεγονός B.