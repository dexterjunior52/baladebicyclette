
import java.util.Scanner;

public class BaladeBicyclette {

    public static void main ( String [] args ) {

        Scanner sc = new Scanner ( System.in );


        System.out.println ( "Quel temps fera-t-il demain ? (beau/pas beau) : ");

        String meteo = scanner.nextLine();

        if (meteo.equalsIgnoreCase ( "beau" )) {
            System.out.println ( "Faire une balade à bicyclette.");

            System.out.println ( "Vérifier l'état de la bicyclette.");

            System.out.println ("Si la bicyclette ne fonctionne pas, aller à pied jusqu'à l'étang.");

            System.out.println ("Sinon, passer chez le garagiste pour réparer la bicyclette.");

        } else if (meteo.equalsIgnoreCase ("pas beau")) {

            System.out.println ("Consacrer la journée à la lecture.");

            System.out.println ("Chercher le 1er tome de \"Game of Thrones\" dans la bibliothèque.");

            System.out.println ("Si le livre est disponible, s'installer confortablement et commencer la lecture.");

            System.out.println ("Sinon, emprunter un roman policier à la bibliothèque municipale.");

        } else {
            System.out.println ("Météo non reconnue. Veuillez entrer \"beau\" ou \"pas beau\".");


        }
