<!doctype html>
<html lang="en">
  <head>
    <title>ASTRickPattern🅰</title>
    <link rel="shortcut icon" href="🅰" type="image/x-icon">
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <style>
    body{
        background-image:url(Screenshot_2022-10-03-09-24-55-006_com.miui.gallery.jpg);
        
    }
    /******************************************************/
    .h1{color: rgb(0, 179, 255);
    font-family:monospace;
text-align: center;}
/******************************************************************************************/
.h2{color: rgb(255, 0, 144);
    font-family:monospace;
}
/******************************************************************************************/
pre{color: rgb(255, 255, 255);}
h2{color: rgb(0, 166, 255);}
/******************************************************************************************/
#d {
        display: flex;
        justify-content: center;
        align-items: center;
    overflow: hidden;
        min-height: 70vh;
      }
      .box {
        position: relative;
        height: 200px;
        width: 200px;
        transform-style: preserve-3d;
        animation: animate 20s linear infinite;
      }
      @keyframes animate {
        0% {
          transform: perspective(1000px) rotateY(0deg);
        }
        100% {
          transform: perspective(1000px) rotateY(360deg);
        }
      }
      .box span {
        border: 1px solid white;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        transform-origin: center;
        transform-style: preserve-3d;
        transform: rotateY(calc(var(--i) * 45deg)) translateZ(400px);
        -webkit-box-reflect: below 5px
          linear-gradient(transparent, transparent, #0004);
      }
      .box span img {
        position: absolute;
        top: 0%;
        left: 0%;
        width: 100%;
        height: 100%;
        object-fit: fill;
      }
      /********************************************************/
      #uu{
        font-family: monospace;
        white-space: nowrap;
        width:22ch;
        
        overflow:hidden ;
        transition: all;
        animation:aa 5s steps(22) ;
        animation-iteration-count:3;
      }
      @keyframes aa{
        0%{width:0%;}
      }
  </style>
</head>
  <body>
    <nav class="navbar navbar-expand-md navbar-dark">
        <a class="navbar-brand" href="#">Amar Mishra</a>
           
        </div>
    </nav>
      <h1 class="h1"><b> Astrick Patterns</b></h1>
      <h3></h3>
      <div class="container" id="d" style="color: white">
        <div class="box">
          <span style="--i: 1"><img src="hexagonal.c - .vscode - Visual Studio Code 24-09-2022 09_46_48.png" alt="" /></span>
          <span style="--i: 2"><img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_40_26.png" alt="" /></span>
          <span style="--i: 3"><img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_41_01.png" alt="" /></span>
          <span style="--i: 4"><img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_41_28.png" alt="" /></span>
          <span style="--i: 5"><img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_42_50.png" alt="" /></span>
          <span style="--i: 6"><img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_43_30.png" alt="" /></span>
          <span style="--i: 7"><img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_44_19.png" alt="" /></span>
          <span style="--i: 8"
            ><img src="Screenshot (23).png" alt=""
          /></span>
        </div>
      </div>
  <div class="container">
    <ul class="nav nav-tab">
      <li class="nav-item"><a href="#c1" class="nav-link active" data-toggle="tab">triangle</a></li>
      <li class="nav-item"><a href="#c2" class="nav-link" data-toggle="tab">cuboid</a></li>
      <li class="nav-item"><a href="#c3" class="nav-link" data-toggle="tab">Squre_with_diagonal</a></li>
      <li class="nav-item"><a href="#c4" class="nav-link" data-toggle="tab">Triangle_with_diagonal</a></li>
      <li class="nav-item"><a href="#c5" class="nav-link" data-toggle="tab">Hut</a></li>
      <li class="nav-item"><a href="#c6" class="nav-link" data-toggle="tab">Open Hexagon</a></li>
      <li class="nav-item"><a href="#c7" class="nav-link" data-toggle="tab">Hexagon</a></li>
      <li class="nav-item"><a href="#c8" class="nav-link" data-toggle="tab">Pentagon</a></li>
    </ul>
    <br><br><br>
    <div class="tab-content">
      <div class="tab-pane container active" id="c1">
<img src="Screenshot (23).png" width="100%"  alt="">
<h2>code-></h2>
<pre>
  #include< iostream>
    using namespace std;
    int main(){
        int m;
        cin>>m;
        for(int i=0;i<=m-1;i++){
            for(int j=0;j<=i-1;j++){
                cout<<"*";
            }
            cout<<"\n";
        }
        return 0;
    }
</pre>
      </div>
      <div class="tab-pane container fade" id="c2">
        <img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_44_19.png" width="100%" alt="">
        <h2>code-></h2>
        <pre>
          #include< iostream>                
          #include< conio.h>                                                                                                                
          using namespace std;
          int main(){
              int n,a=1;//input
              cout<<"enter the no.\n";
              cin>>n;
              int k=(2*n)+1;
              int m=k/2;
              int l=k+m;
              int i,j;
              for(i=l;i>=1;i--){
                  for(j=1;j<=l;j++){
                      if(i==j||(i==1&&j<=k)||(j==k&&i<=k)||(j==1&&i<=k)||(j==m&&i<=l&&i>=m)||(j==l&&i<=l&&i>=m)
                      ||(i==k&&j<=k)||(i==1&&j<=k)||(i==l&&j<=l&&j>=m)||(i==m&&j<=l&&j>=m)){
                          cout<<"*";
                      }
                     
                      //if(i==1&&j<=k)cout<<"*";
                      //if(j==k&&i<=k-1)cout<<"*";
                      else{
                          cout<<" ";
                      }
                  }
                  cout<<"\n";
                   a++;
              }
              getch();
              return 0;
          }</pre>
      </div>
      <div class="tab-pane container fade" id="c3">
        <img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_43_30.png" width="100%" alt="" srcset="">
      <h2>code-></h2>
      <pre>#include< iostream>
        using namespace std;
        int main()
        {
            int edgeLength;
            cout<<"enter edge length \n";
            cin>>edgeLength;
            int i,j;
            for(i=edgeLength;i>=1;i--){
                for(j=1;j<=edgeLength;j++){
                    if(j==1||j==edgeLength||i==j||i==1||i==edgeLength||i+j==(edgeLength+1)){
                        cout<<"*";}
                    else
                    {cout<<" ";}}
                cout<<"\n";
            }
            return 0;
        }</pre>
      </div>
      <div class="tab-pane container fade" id="c4">
        <img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_42_50.png" width="100%" alt="">
        <h2>code-></h2>
        <pre>
          #include< iostream>
            using namespace std;
            int main(){
            int length;
            cout<<"enter the value \n";
            cin>>length;
            int i,j,k=0;
            for(i=length;i>=1;i--){
                for(j=i;j>=1;j--){
                    cout<<" ";
                }
                int m=(2*k)+1;
                for(j=1;j<=m;j++){
                    if(j==1||j==m||j==((m+1)/2)||i==1){cout<<"*";}
                    else
                    {cout<<" "; }}
                cout<<"\n";
                k++;
                
            }
            }
        </pre>
      </div>
      <div class="tab-pane container fade" id="c5">
        <img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_41_28.png" width="100%" alt="">
        <h2>code-></h2>
        <pre>
          //astrick hut
#include< iostream>
using namespace std;

int main(){
    int n;
    cout<<"enter the number \n";
    cin>>n;
    int k=(2*n)+1;//row
    int l=2*k;//col
    for(int i=0;i<=k-1;i++){//i represents row
        for(int j=0;j<=l-1;j++){//j represents col
            if((i==0&&j>l/4&&j<(3*l)/4)||(i==k-1)||(i>l/4&&(j==0||j==k-1||j==l-1))||(i+j==(l/4))
            ||(i+j==(l/4)+(2*i)&&i< l/4+1)
            ||(i+j==((3*l)/4)+(2*i)&&i< l/4+1)||(i==l/4&&j>=l/2)||((j==(n+(n/3))||j==(n-(n/3)))&&i>l/3)
            ||((j<=(n+(n/3))&&j>=(n-(n/3)))&&i==l/3)){
                cout<<"*";
            }
            else{
                cout<<" ";
            }
        }
        cout<<"\n";
    }
    return 0;
}
        </pre>
      </div>
      <div class="tab-pane container fade" id="c6">
        <img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_40_26.png" width=100% alt="">
       <h2>code-></h2>
        <pre>
          #include< iostream>
          #include< conio.h>
          using namespace std;
          int main(){
          
              int n;
              cout<<"enter the no. \n";
              cin>>n;
              int k=2*n-1;
              int l=3*k;
              int m=(2*k)+(k-2);
              for(int i=0;i< m;i++){
                  for(int j=0;j< l;j++){
                      if((i<(2*l)/3&&i>l/3)&&((j==0||j==k-1)||(j>k+(k-2)&&j< m))//middle section
                      ||(i+j==k)||(i+j==k+k&&i< k+1)||(i+j>=(k)+2*i&&i+j<=k+k-2+(2*i)&&i< k)//upper section()
                      ||(i>2*k&&(i+j>4*k-2)&&i+j< 5*k-2)||(i>2*k-1&&i+j>(k*2)+2*i&&i+j< k+k+k+i)
                      )cout<<"*";
          
                      else{cout<<" ";}
                  }cout<< endl;
              }
              getch();
              return 0;
          }</pre>
      </div>
      <div class="tab-pane container fade" id="c7">
        <img src="hexagonal.c - .vscode - Visual Studio Code 24-09-2022 09_46_48.png" width="100%" alt="" >
        <h2>code-></h2>
        <pre>#include< stdio.h>
          #include< conio.h>
          int main()
          {
              
              int i,c;
              int a,b,d,e,f,g,h,j,k,l,m,n;
          printf("enter the side edge :");
          scanf("%d",&a);//edge length
          c=a;
          e=0;
          for(i=a;i>=1;--i){
              for(b=1;b<=c;b++){
                  printf(" ");
              }
              f=1+(2*e);
              for(d=1;d<=f;d++){
                  printf("*");
              }
              printf("\n");
              c--;
              
              e++;
          }
          //next rectangle starts
          for(g=(a+1);g>=1;--g){
              for(h=1;h<=(f+2);h++){
                  printf("*");
              }
              printf(" ");
              printf("\n");
          }
          //reverse triangle
          k=1;
          n=0;
          for(i=a;i>=1;--i){
              for(j=1;j<=k;j++)
              {
                  printf(" ");
              }
              
              m=f-(2*n);
              for(l=1;l<=m;l++)
              {
                  printf("*");
              }
              printf("\n");
              k++;
              n++;
          }
          getch();
          }
          
          </pre>
      </div>
      <div class="tab-pane container fade" id="c8">
        <img src="hexagonAM.cpp - .vscode - Visual Studio Code 24-09-2022 09_41_01.png" width="100%" alt="">
        <h2>code-></h2>
        <pre>
          #include< iostream>
            using namespace std;
            int main()
            {
               int edgeLength;
               int i;
               int n,l,k=0,p,r;
               cout<<"enter the edge";
               cin>>edgeLength;
               for(i=edgeLength;i>=1;i--)
               {
                for(n=1;n< i;n++){cout<<" ";}
                int m=2*k+1;
                for(l=1;l<=m;l++){(l==m||l==1)?cout<<"*": cout<<" ";}
                cout<<"\n";
                k++;
                r=m;
               }
               for(i=edgeLength-2;i>=1;i--){
                
            for(p=1;p<=r;p++){
               if(p==1||p==r||i==1){
                  cout<<"*";}
               else{cout<<" ";}}
            cout<<"\n";}
            return 0; 
            }
        </pre>
      </div>
    </div>
    <br><br><br>

    <h1 class="h1 " id="uu">Thanks to visit <b class="h1" >.....</b></h1>
  </div> 

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
