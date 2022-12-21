#include<stdio.h>
int binarySearch(int arr[], int low, int high, int element){
	int mid= (low+high)/2;
	if (arr[mid]==element){
		return mid;
	}
	else if (arr[mid]<element){
		return binarySearch(arr, mid+1, high, element);
	}
	else{
		return binarySearch(arr, low, mid-1, element);
	}
	return -1;
}

int main(){
	int arr[10],low=0,high=9,element;
	printf("Enter the elements in ascending order");
	for (i=0, i<10, i++){
		scanf("%d",&arr[i]);
	}
	printf("Enter the element to be searched: ");
	scanf("%d",&element);
	int found=binarySearch(arr, low, high, element);
	if (found==(-1)){
		printf("The element is not found !!!");
	}
	else{
		printf("The element %d is present at index %d",element,found);
	}
}
