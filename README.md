# Variaveis Java
## Explicações das Variaveis

public class Main {
    public static void main(String[] args) {
        VariablesJava variablesJava = new VariablesJava();

        int variavelInt = 100;
        byte variavelByte = 20;
        long variavelLong = 20000;
        short variavelShort = 1;
        float variavelFloat = 11.09f;
        double variavelDouble = 100.456;
        String variavelString = "Hello Darkness, my old friend";
        boolean variavelBoolean = false;

        variablesJava.setVariavelInt(variavelInt);
        variablesJava.setVariavelByte(variavelByte);
        variablesJava.setVariavelLong(variavelLong);
        variablesJava.setVariavelShort(variavelShort);
        variablesJava.setVariavelFloat(variavelFloat);
        variablesJava.setVariavelDouble(variavelDouble);
        variablesJava.setVariavelString(variavelString);
        variablesJava.setVariavelBoolean(variavelBoolean);


        System.out.println("Int: Numeros inteiros de 32 bits," + variablesJava.getVariavelInt());
        System.out.println("Byte: Numeros inteiros de 8 bits," + variablesJava.getVariavelByte());
        System.out.println("Long: Numeros inteiros de 64 bits," + variablesJava.getVariavelLong());
        System.out.println("Short: Numeros inteiros de 16 bits," + variablesJava.getVariavelShort());
        System.out.println("Float: Numeors em notacao de ponto flutuante" + variablesJava.getVariavelFloat());
        System.out.println("Double: Numeors em notacao de ponto flutuante" + variablesJava.getVariavelDouble());
        System.out.println("String: aceita caracteres alfanumericos entre aspas" + variablesJava.getVariavelString());
        System.out.println("Boolean: Pode assumir dois valores (true e false)" + variablesJava.getVariavelBoolean());

    };
}
