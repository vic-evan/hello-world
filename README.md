# hello-world
public class seasonTest{
public static void main(String args []){
season season1 = new season(SPRING);
  
System.out.println();
}
enum season{
  SPRING("春天","Spring"),
  SUMMER("夏天","Summer"),
  AUTUMN("秋天","Autumn"),
  WINTER("冬天","Winter");

  private String seasonName;
  private String seasonDesc;
  
  private season(String seasomName , String seasonDesc){
    this.seasonName = seasonName;
    this.seasonDesc = seasonDesc;
  }
  
  private String getSeasonName(){
    return seasonName;
}
  pivate String getSeasonDesc(){
    return seasonDesc;
  }

}
