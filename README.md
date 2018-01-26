# Pacman
* [Github Page παιχνιδιού](https://p13seva.github.io/)

#Σύνοψη
Η παρούσα αναφορά δημιουργήθηκε στα πλαίσια του μαθήματος, 6ου εξαμήνου, “Τεχνολογία Λογισμικού”. Σκοπός είναι η περιγραφή της εξαμηνιαίας εργασίας του μαθήματος, με αντικείμενο την επέκταση του παιχνιδιού Pacman -ένα HTML5 video game–.

Για την εύρεση της εργασίας, χρήσιμα link είναι τα παρακάτω:

*[Προσωπικό αποθετήριό](https://github.com/p13seva/pacman)
*[Παιχνίδι](https://p13seva.github.io/pacman/)
*[Github Page παιχνιδιού](https://p13seva.github.io/)

#Εισαγωγή
Το Pacman είναι αποτελεί στις μέρες μας ένα κλασικό βιντεοπαιχνίδι, στα πλαίσια της εργασίας επιχειρήθηκε η ανανέωσή του με την προσθήκη σ’αυτό των χαρακτήρων απο κλασικά κινούμενα σχέδια.

#Επιλογή εργαλείων
Η ανάπτυξη του κώδικα του παιχνιδιού, ο οποίος βρίσκεται στο αρχείο index.html, έγινε μέσω του Github και δεν χρησιμοποιήθηκε κάποιος επεξεργαστής κειμένου. Ωστόσο, για την κατασκευή της νέας πίστας χρησιμοποιήθηκε ως εργαλείο το λογισμικό Tiled.

#Διαδικασία ανάπτυξης
Στα πλαίσια του 1ου παραδοτέου, η μοναδική αλλαγή που πραγματοποιήθηκε στον δοθέντα κώδικα είναι η αλλαγή

this.load.baseURL = 'https://p13seva.github.io/pacman/';

Στα πλαίσια του 2ου παραδοτέου του μαθήματος, απ’ όπου και ξεκίνησε ουσιαστικά η ανάπτυξη του παιχνιδιού, πραγματοποιήθηκε η αλλαγή του πρωταγωνιστή του παιχνιδιού, η προσθήκη επιπλέον αντικειμένων καθώς και η δημιουργία μιας νέας πίστας. Πιο συγκεκριμένα, ο πρωταγωνιστής Pacman αντικαταστάθηκε από τον Martian (χαρακτήρα των looney tunes) και οι αρχικές κουκίδες (dots) αντικαταστάθηκαν από πλανήτες. Επιπλέον, τη θέση της αρχικά δοθείσας πίστας πήρε μια νέα, με την ανατοποθέτηση των tiles του δοθέντος tileset στο χώρο της πίστας. Η νέα αυτή πίστα δημιουργήθηκε με τη χρήση του Tiled.

Ο πρωταγωνιστής και τα αντικείμενα που χρησιμοποιήθηκαν είναι:

  file:///Users/Kissamitakis/Downloads/Marvin-Martian-icon.png   

Η νέα πίστα που δημιουργήθηκε είναι:



Στη συνέχεια, στα πλαίσια του 3ου παραδοτέου, το παιχνίδι προεκτάθηκε, με τη προσθήκη score και ήχου. Πιο συγκεκριμένα, στο πάνω μέρος της οθόνης που βλέπει ο χρήστης, προστέθηκε το score που συγκεντρώνει ο παίκτης μαζεύοντας τους πλανήτες της πίστας.Επίσης, προστέθηκε ήχος ο οποίος ακούγεται καθ’ όλη τη διάρκεια του παιχνιδιού.Τέλος προστέθηε και ενας εχθρός, ο οποίος κινείται τυχαία στην πίστα.
