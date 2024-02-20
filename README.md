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

this is insertion sort code




var arr=[4,3,2,5,1];
for(var i=0;i<arr.length-1;i++){
    for(var j=i+1;j>=i-1;j--){
        if(arr[j]>arr[j-1]){
            var y=arr[j-1];
            arr[j-1]=arr[j];
            arr[j]=y;
        }
    }
}console.log(arr)

this is bubble sort algo

