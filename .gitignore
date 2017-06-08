public class Solution {
    public char findTheDifference(String s, String t) {
        char[] arrayOne = s.toCharArray();
        char[] arrayTwo = t.toCharArray();
        
        Arrays.sort(arrayOne);
        Arrays.sort(arrayTwo);
        
        for(int a = 0; a < arrayOne.length; a++) {
            if(arrayOne[a] != arrayTwo[a])
                return arrayTwo[a];
        }
        
        return arrayTwo[arrayTwo.length - 1];
    }
}
