# java1
package com.company;

import javax.sound.midi.SysexMessage;

public class Main {

    public static void main(String[] args) {
	// write your code here
        int[] Array = new int[100];
        for(int i=0;i<Array.length;i++){
            Array[i] = (int)(10 + (Math.random() * (56 - 10)));
            System.out.println(Array[i]);

        }
    }
}
