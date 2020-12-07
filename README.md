# trabajo-final-progra-
public void selecAplicación(){
String opcion = " "; do{ opcion = JOptionPane.showInputDialog(null,"Ingrese el nombre de la aplicación que desea abrir \n" + " Whatsapp\n" + "Facebook\n" + "Agenda\n" + "Marcador\n" + "Banco\n" + "Instagram\n" + "Volver" ).toUpperCase();

switch(opcion){ case "WHATSAPP": JOptionPane.showMessageDialog(null,"La aplicacion WhatsApp ha sido abierta\n" ); JOptionPane.showInputDialog("Ingrese el nombre de un contacto"); break; case "FACEBOOK": JOptionPane.showMessageDialog(null,"La aplicacion Facebook ha sido abierta\n" ); break; case "AGENDA": JOptionPane.showMessageDialog(null,"La aplicacion Agenda ha sido abierta"); break; case "MARCADOR": JOptionPane.showMessageDialog(null,"La aplicacion Marcador ha sido abierta"); break; case "BANCO": JOptionPane.showMessageDialog(null,"La aplicacion Banco ha sido abierta"); break; case "INSTAGRAM": JOptionPane.showMessageDialog(null,"La aplicacion Instagram ha sido abierta"); break; case "VOLVER": JOptionPane.showMessageDialog(null,"Cerrando módulo de aplicaciones"); break;

       default: 
           JOptionPane.showMessageDialog(null,"La palabra ingresada no corresponde a ninguna aplicación");
            break;
}

} while( opcion != "VOLVER");

}
}
