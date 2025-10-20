# level1-task2
int main() {
  int a,b;
  
  cout<< "iki tam eded daxil edin" ;
  cin>> a >> b ;
  
  cout<< "cem: " << a+b <<endl;
  cout<< "ferq: " << a-b <<endl;
  cout<< "hasil: " << a*b <<endl;
  
  if (b!=0)
    cout<< "bolme: "<< (double)a / b <<endl;
  else
    cout<< "bolme: mumkun deyil (sifira bolmek olmaz)"<<endl; 
return 0;
}
