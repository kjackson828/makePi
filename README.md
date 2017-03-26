# makePi

public int[] makePi() {
    double pi = Math.PI; 
    int[] piArray = new int[3];
    for (int i = 0; i < 3; i++) {
      piArray [i] = (int) pi % 10;
      pi = pi*10;
    }
    return piArray;
}
