# Μάθημα:Επικοινωνια ανθρωπου υπολογιστη


### Ονοματεπώνυμο:Θεόφιλος Παναγιώτης Παπαδόπουλος
### Αριθμός Μητρώου: Π2019136

## Παραδοτέο 1

| Εβδομάδα* | Παραδοτέο |
| --- | --- |
| 1 | Φορκ του αποθετηρίου και δημιουργία της σελίδας της αναφοράς με τα προσωπικά στοιχεία σας, της σύνοψης με αυτόν τον πίνακα περιεχομένων, και συγγραφή της εισαγωγής με περιγραφή των αναγκών και των στόχων σας για το αντίστοιχο μάθημα* |
| 2 | Άσκηση προγραμματισμού |
| 3 | Άσκηση γραμμής εντολών |
| 4 | Άσκηση προγραμματισμού + αίτημα ενσωμάτωσης (CSCW, IV) |
| 5 | Άσκηση γραμμής εντολών |
| 6 | Άσκηση προγραμματισμού (HCI) ή γραμμής εντολών (SW)+ συμμετοχικό περιεχόμενο |
| 7 | Άσκηση γραμμής εντολών (SW) + αίτημα ενσωμάτωσης (CSCW, IV) |
| 8 | Άσκηση προγραμματισμού (HCI) ή γραμμής εντολών (SW) |
| 9 | Άσκηση γραμμής εντολών (SW) ή αίτημα ενσωμάτωσης (CSCW, IV) |
| 10 | συμμετοχικό περιεχόμενο |
| 11 | αίτημα ενσωμάτωσης (CSCW, IV) |
| 12 | Τελική αναφορά* |

Στόχοι για αυτό το μάθημα : Ως βασικός στόχος για το μάθημα είναι η μελέτη της θεωρίας και η πρακτική εξάσκηση στην σχεδίαση και ανάπτυξη της διάδρασης όπως αναφέρει και το μάθημα Όμως ως προσωπικούς στόχους έχω θέσει τους εξής : Πρώτα από όλα θέλω να αρχίσω να χρησιμοποιώ καινούργια εργαλεία για τον υπολογιστή. Ένα από αυτά τα "εργαλεία" που θα προσπαθήσω να μάθω είναι το Github το οποίο πιστεύω θα μπορώ να χρησιμοποιήσω αρκετά στο μέλλον αν τελικά αποφασίσω να ακολουθήσω μια καριέρα ως προγραμματιστής. Επίσης η δοκιμή καινούργιων λειτουργικών συστημάτων όπως linux θα ήταν επιθυμητή καθώς ανοίγονται καινούργιες δυνατότητες για έναν προγραμματιστή. Έπειτα η εξερεύνηση καινούργιων γλωσσών προγραμματισμού όπως Java, python αλλά και ψευδογλώσσες όπως η html και css για την δημιουργία και ολοκλήρωση των project για το μάθημα Τέλος η επικοινωνία με γνωστές στο αντικείμενο όπως προγραμματιστές αλλά ακόμη και τους συμφοιτητές μου.

## Παραδοτέο 2

Για το δευτερο παραδοτεο μας δωθηκε η επιλογη να διαλεξουμε απο μια πληθωρα ασκησεων. Η ασκηση που επελεξα εγω μου εδινε τον κωδικα για ενα κουμπι και επρεπει να τροποποιηθει καταληλα ο κωδικας ωστε να συμβαινει κατι που θελω οταν καποιος παταει το κουμπι. Μετα απο την μελετη που εκανα πανω στις γλωσσες html, css και js επεξεργαστικα καταλειλα τον κωδικα ωστε να εμφανιζεται σε ενα αλλο παραθειρο ενα τραγουδι της επιλογης μου.
link για το codepen:https://codepen.io/p2019136/pen/NWrrqdV


<div class="codepen" data-height="406" data-theme-id="light" data-default-tab="css,result" data-user="p2019136" data-slug-hash="NWrrqdV" data-prefill='{"tags":[],"scripts":[],"stylesheets":[]}'>
  <pre data-lang="html">&lt;a class="button" href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstleyVEVO" target="_blank" role="button">
	&lt;span>Hello&lt;/span>
	&lt;div class="icon">
		&lt;i class="fa fa-remove">&lt;/i>
		&lt;i class="fa fa-check">&lt;/i>
	&lt;/div>
&lt;/a></pre>
  <pre data-lang="scss">$color: #c0392b;
$color-dark: #a53125;
$speed: "0.25s";
$transition: all #{$speed} cubic-bezier(0.310, -0.105, 0.430, 1.400);

* {
    margin: 0;
    padding: 0;
    box-sizing: inherit;

    &:focus {
        outline: none;
    }
}

html {
    box-sizing: border-box;
}

body {
    background-color: #000;
    font-family: 'Open Sans', sans-serif;
}

.button {
    display: block;
    background-color: $color;
    width: 300px;
    height: 100px;
    line-height: 100px;
    margin: auto;
    color: #fff;
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    cursor: pointer;
    overflow: hidden;
    border-radius: 5px;
    box-shadow: 0 0 20px 0 rgba(0,0,0,.3);
    transition: $transition;
    
    span,
    .icon {
        display: block;
        height: 100%;
        text-align: center;
        position: absolute;
        top: 0;
    }
    
    span {
        width: 72%;
        font-size: 22px;
        text-transform: uppercase;
        left: 0;
        transition: $transition;
        
        &:after {
            content: '';
            background-color: $color-dark;
            width: 2px;
            height: 70%;
            position: absolute;
            top: 15%;
            right: -1px;
        }
    }
    
    .icon {
        width: 28%;
        right: 0;
        transition: $transition;
        
        .fa {
            font-size: 30px;
            vertical-align: middle;
            transition: $transition, height #{$speed} ease;
        }
        
        .fa-remove {
            height: 36px;
        }
        
        .fa-check {
            display: none;
        }
    }
    
    &.success,
    &:hover {
        
        span {
            left: -72%;
            opacity: 0;
        }
        
        .icon {
            width: 100%;
            
            .fa {
                font-size: 45px;
            }
        }
    }
    
    &.success {
        background-color: #97e466;
        
        .icon {
            
            .fa-remove {
                display: none;
            }
            
            .fa-check {
                display: inline-block;
            }
        }
    }
    
    &:hover {
        opacity: .9;
        
        .icon .fa-remove {
            height: 46px;
        }
    }
    
    &:active {
        opacity: 1;
    }
}</pre>
  <pre data-lang="coffeescript">removeSuccess = ->
	$('.button').removeClass 'success'

$(document).ready ->
	$('.button').click ->
		$(@).addClass 'success'
		setTimeout removeSuccess, 3000</pre></div>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
