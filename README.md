package com.kuliah;

import java.util.HashSet;
import java.util.Iterator;
import java.util.Set;


public class TugasSet {

    public static void main(String[] args) {

// PROGRAM SET

        Set<String> awatara = new HashSet<>();

        awatara.add("Matsya");
        awatara.add("Kurawa");
        awatara.add("Waraha");
        awatara.add("Narasinga");
        awatara.add("Wamana");
        awatara.add("Parasurama");
        awatara.add("Rama");
        awatara.add("Rama");
        awatara.add("Krishna");
        awatara.add("Buddha");
        awatara.add("Kalki");

        System.out.println("Dasa awatara : (size = " + awatara.size() +")");
        for (String a : awatara) {
            System.out.println("\t " + a);
        }

        awatara.remove ("Kalki");

        System.out.println("\nAwatara yang telah lahir ke bumi : ");
        for (Iterator iterator = awatara.iterator(); iterator.hasNext();){
            System.out.println("\t" + iterator.next());
        }
    }
}
