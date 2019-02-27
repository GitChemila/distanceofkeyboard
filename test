class Solution {
    public int solution(String S1, String S2) {
        // write your code in Java SE 8
        int x=S2.length();
        int last=0; 
        int temp=0;
        int sum=0;
        for(int i=0;i<x;i++){
        
        temp=S1.indexOf(S2.charAt(i));
        sum=sum+Math.abs(last-temp);
        last=temp;
        }
        
        return sum;
    }
}
