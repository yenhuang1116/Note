```
void bubbleSort(int* in, int n){
	char isChange = -1;
	for(int i=n-1;i>0;i--){
		isChange = -1;
		for(int j=0;j<i;j++){
			if(in[j]>in[j+1]){
				swap(&in[j], &in[j+1]);
				isChange = 1;
			}
		}
		if(-1==isChange){
			break;
		}		
	}
}

```
