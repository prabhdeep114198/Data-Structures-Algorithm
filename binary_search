import java.util.Scanner;

public class binarysearch {
    public static int bs(int[] arr, int a) {
        int l = 0;
        int r = arr.length - 1;

        while (l <= r) {
            int mid = l + (r - l) / 2;
            if (arr[mid] == a) {
                return mid;
            }
            if (arr[mid] < a) {
                l = mid + 1;
            }

            else {
                r = mid - 1;
            }
        }

        return -1;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("enter size of array");
        int m = sc.nextInt();
        int arr[] = new int[m];
        System.out.println("enter the elements of an array");
        for(int i =0; i<m;i++){
            arr[i] = sc.nextInt();
        }
        System.out.println("enter element to search");
        int a = sc.nextInt();
        int index = bs(arr, a);
        if (index != -1) {
            System.out.println("Element found at index: " + index);
        } else {
            System.out.println("Element not found in the array.");
        }
    }
}
