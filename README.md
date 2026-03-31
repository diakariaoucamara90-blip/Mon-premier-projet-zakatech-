<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <Title>Les formulaires</Title>
    </head>

    <body>
        <FORM>
            <h2>Fiche d'identification :</h2><br>

            <TABLE Border="4">
                <TR>
                    <TD>Votre Nom :</TD>
                    <TD>
                        <Input type="text" name="nom">
                    </TD>
                </TR>
                <TR>
                    <TD>Votre Prénom :</TD>
                    <TD>
                        <Input type="text" name="prenom">
                    </TD>
                </TR>
                <TR>
                    <TD>Sexe :</TD>
                    <TD>
                        Homme : <Input type="radio" name="sexe" Value="M"><BR>
                        Femme : <Input type="radio" name="sexe" Value="F">
                    </TD>
                </TR>
                <TR>
                    <TD>Fonction :</TD>
                    <TD>
                        <SELECT name="fonction">
                            <OPTION VALUE="Enseignant">Enseignant</OPTION>
                            <OPTION VALUE="Etudiant">Etudiant</OPTION>
                            <OPTION VALUE="Ingénieur">Ingénieur</OPTION>
                            <OPTION VALUE="Retraité">Retraité</OPTION>
                            <OPTION VALUE="Autre">Autre</OPTION>
                        </SELECT>
                    </TD>
                </TR>
                <TR>
                    <TD>Commentaires :</TD>
                    <TD>
                        <TextArea rows="3" name="commentaires">Tapez ici vos commentaires</TextArea>
                    </TD>
                </TR>
                <TR>
                    <TD Colspan=2>
                        <Input type="Submit" value="Envoyer">
                    </TD>
                </TR>
            </TABLE>
        </FORM>
    </body>
</html>
