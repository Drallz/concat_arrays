public static void main(String[] args) {
        int[] u = {2, 5, 8};
        int[] v = {9,0 ,6};
        int len = u.length + v.length;
        int[] o = new int[len];
        for (int i = 0;i < u.length;++i){
            o[i ] = u[i];

        }
       for (int i = len/2;i < len;++i){
            o[i] = v[i-3];

        }
        for (int i : o){
            System.out.println(i);
        }
        // java code on concatenating two arrays into one array and print the output
