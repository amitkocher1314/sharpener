# sharpener
var arr=[1,4,3,2,7,9];
for(i=1;i<arr.length;i++){
    var temp=arr[i];
    var j=i-1;
    while(j>=0 && temp>arr[j]){
       
        
        temp=arr[j+1];
        arr[j+1]=arr[j];
        arr[j]=temp;
         j=j-1;
    }
    arr[j+1]=temp;
    console.log(arr);
}
