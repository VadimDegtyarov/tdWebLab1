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

>>>>>>> a4d110730e02c533585c6689ffd025d1fe3531f5
