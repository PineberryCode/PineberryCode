```JAVA
public class ME {
  
  private String studying_professionalCareer;
  private String[] mySkills;
  private String[] pronouns;
  
  public ME () {}
  
  public String getProfessionalCareer () { return professionalCareer; }
  public void setProfessionalCareer ( String professionalCareer ) { this.professionalCareer = professionalCareer; }
  
  public String[] getMySkills () { return mySkills; }
  public void setMySkills ( String[] mySkills ) { this.mySkills = mySkills; }
  
  public String[] getPronouns () { return pronouns; }
  public void setPronouns ( String[] pronouns ) { this.pronouns = pronouns; }
  
  public void show () {
    System.out.println("Career:"+this.getProfessionalCareer());
    System.out.println("Skills:");
    for (int i=0; i<this.mySkills.length;i++){
      System.out.println(this.mySkills[i]);
    }
    System.out.println("Pronouns:");
    for (int j=0; j<this.pronouns.length;j++){
      System.out.println(this.pronouns[j]);
    }
  }
  
  public static void main(String[] args) {
    TestAN T = new TestAN();
    T.setProfessionalCareer("Systems Engineering");
    T.setMySkills(new String[]{"JAVA","T-SQL","Javascript","HTML","CSS"});
    T.setPronouns(new String[]{"He","Him"});
    T.show();
  }
}
```
