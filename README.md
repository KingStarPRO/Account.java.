package Examen;

import java.util.Random;

public class Account {

    private String name;

    private Bill bill;

    public Bill getBill() {
        return bill;
    }

    public void setBill(Bill bill) {
        this.bill = bill;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public Account() { }

    public Account(String name, Bill bill) {
        this.name = name;
        this.bill = bill;
    }

    @Override
    public String toString() {
        return "Account{" +
                "name='" + name + '\'' +
                ", bill=" + bill +
                '}';
    }
}
