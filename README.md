public class CollegeAdmissionForm {

    public static void main(String[] args) {
        // Personal Information
        String lastName = "Khandavalli";
        String firstName = "praneetha";
        String middleName = "Jahnavi";
        String completeAddress = "1-43,Rusthumbadha";
        String dateOfBirth = "2003-07-27";
        String birthplace = "Narsapur";
        String citizenship = "indian";
        String civilStatus = "Single";
        String sex = "Female";
        String contactNumber = "09123456789";
        String religion = "Hindu";
        String nameOfSpouse = "N/A";
        String contactNumberOfSpouse = "N/A";

        // Father's Information
        String fatherName = "Naryana Acharyalu";
        String fatherOccupation = "";
        String fatherContactNumber = "09998887777";

        // Mother's Information
        String motherName = "Sitha Rama Lakshmi";
        String motherOccupation = "Teacher";
        String motherContactNumber = "09887776666";

        // Guardian's Information
        String guardianName = "Bro";
        String guardianContactNumber = "09112223333";
        String guardianAddress = "1-43,Narsapur";

        // Senior High School Info
        String seniorHighSchool = "National High School";
        String shsStand = "STEM";
        int yearGraduated = 2025;
        float generalAverage = 80.05f;

        // Transferee/Graduate Info
        String lastSchoolAttended = "SCET";
        String course = "ECE";
        String lastSchoolYear = "2021-2025";

        // Other Information
        boolean isAlsPasser = false;
        int alsYearTaken = 0;
        float alsAverage = 0.0f;

        boolean is4PsBeneficiary = true;
        String id4Ps = "4PS123456789";

        boolean isPwd = false;
        String typeOfDisability = "N/A";

        // Print all values without if statements
        System.out.println("----- APPLICATION FOR COLLEGE ADMISSION TEST -----");
        System.out.println("Last Name: " + lastName);
        System.out.println("First Name: " + firstName);

        System.out.println("Middle Name: " + middleName);


        System.out.println("Address: " + completeAddress);
        System.out.println("Date of Birth: " + dateOfBirth);
        System.out.println("Birthplace: " + birthplace);
        System.out.println("Citizenship: " + citizenship);
        System.out.println("Civil Status: " + civilStatus);
        System.out.println("Sex: " + sex);
        System.out.println("Contact Number: " + contactNumber);
        System.out.println("Religion: " + religion);
        System.out.println("Spouse Name: " + nameOfSpouse);
        System.out.println("Spouse Contact: " + contactNumberOfSpouse);

        System.out.println("\n----- FATHER'S INFORMATION -----");
        System.out.println("Father's Name: " + fatherName);
        System.out.println("Occupation: " + fatherOccupation);
        System.out.println("Contact: " + fatherContactNumber);

        System.out.println("\n----- MOTHER'S INFORMATION -----");
        System.out.println("Mother's Name: " + motherName);
        System.out.println("Occupation: " + motherOccupation);
        System.out.println("Contact: " + motherContactNumber);

        System.out.println("\n----- GUARDIAN'S INFORMATION -----");
        System.out.println("Guardian Name: " + guardianName);
        System.out.println("Guardian Contact: " + guardianContactNumber);
        System.out.println("Guardian Address: " + guardianAddress);

        System.out.println("\n----- SENIOR HIGH SCHOOL INFORMATION -----");
        System.out.println("School: " + seniorHighSchool);
        System.out.println("Strand: " + shsStand);
        System.out.println("Year Graduated: " + yearGraduated);
        System.out.println("General Average: " + generalAverage);

        System.out.println("\n----- TRANSFEREE / GRADUATE INFORMATION -----");
        System.out.println("Last School Attended: " + lastSchoolAttended);
        System.out.println("Course: " + course);
        System.out.println("School Year: " + lastSchoolYear);

        System.out.println("\n----- OTHER INFORMATION -----");
        System.out.println("ALS Passer: " + isAlsPasser);
        System.out.println("Year Taken: " + alsYearTaken);
        System.out.println("ALS Average: " + alsAverage);
        System.out.println("4Ps Beneficiary: " + is4PsBeneficiary);
        System.out.println("4Ps ID No: " + id4Ps);
        System.out.println("PWD: " + isPwd);
        System.out.println("Disability Type: " + typeOfDisability);
    }
}
