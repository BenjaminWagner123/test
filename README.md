This is a test Repository.

public void testIt{
  DialogBox dialog = new DialogBox();  
  FormPanel form = new FormPanel(); 
  try{
    form.add(new HTML("<br>"); 
    form.setStyleName("formular"); 
    dialog.add(form);
    dialog.setStyleName("dialog"); 
  }catch(IOException e){
    e.printStackTrace; 
  }
  display dialog; 
}
