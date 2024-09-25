# tdWebLab1
ФИО:Дегтярев Вадим Юрьевич  z
Группа:273602

public class SecondThread extends Thread {

    @Override
    public void run(){
        GenMap map = new GenMap();
        map.setSizeMapInSquare(10);
        map.createMap();
        map.getMap();
        map.Walk();
    }
}
