# Classi

public class Utente extends Anagrafica
{
  public int userID;
  /*public int tipologia non so se sia necessario*/
  
  super(/*String nome, String cognome, String email, String codiceFiscale, int telefono*/);
  
  public Utente(/*int userID, String nome, String cognome, String email, String codiceFiscale, int telefono*/)
  {
    this.email=email;
    this.codiceFiscale=codiceFiscale;
    this.nome=nome;
    this.cognome=cognome;
    this.telefono=telefono;
    this.userID=userID;
  }
}
