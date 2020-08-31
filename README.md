# DoctorOffice
package com.company;

public class Main {

    public static void main(String[] args) {

        String patientName = "Stacey Manson";
        boolean hasInsurance = false;
        double temp = 102.2;
        int numVisits = (int) 5.02;
        float copay = (float) 20.95;
        String nextappointmentdate = "September 9, 2020";
        int contactnum = (int) 2026786463;

        System.out.println("Patient Details:");
        System.out.println("Name: "+patientName);
        System.out.println("Patient has insurance: "+hasInsurance);
        System.out.println("Body temprature: " + temp);
        System.out.println("Number of visits: " + numVisits);
        System.out.println("Patient's copay amount: $" + copay);
        System.out.println("Next appointment date: " + nextappointmentdate);
        System.out.println("Contact number: " + contactnum);

    }
}
