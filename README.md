# Anonymous-Inner-class

interface message{

    void text();

}

class code{

    public static void main(String... args){

        message m=new message() {

            @Override

            public void text() {

                System.out.println("Power of java is superb");

            }

        };

        m.text();

        System.out.println(m.getClass().getName());

    }

}

/*

Power of java is superb

code$1 ------ Anonymous inner class

 */
