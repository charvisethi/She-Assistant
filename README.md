#include<iostream>
using namespace std;
void western();
void ethnics();
void winter();
void sports();
void sleepwears();
void welcome();
    int in_Ocassion();
    int in_Style();
    int in_Type();
    int in_Tops();
    int in_Tshirts();
    int in_Shirts();
    int in_Partywear();
    int in_Pfit();
    int in_Cc();
    int in_Rise();   
    int in_Color(); 
    int in_Tfit();
    int in_Tc();           
                int ot_Ocassion();
                int ot_Style();
                int ot_Type();
                int ot_Tops();
                int ot_Tshirts();
                int ot_Shirts();
                int ot_Partywear(); 
    void Fltrs();
char size[3],color[10];
int c,c[10],p[50],price;
int main(){
return 0;
}
void western(){                                                         //incomplete
                cout<<"What are you looking for?"<<endl;
                cout<<"1. Dresses & Jumpsuits"<<endl;
                cout<<"2. Tops,Tshirts & Shirts"<<endl;
                cout<<"3. Jeans & Jeggings"<<endl;
                cout<<"4. Trousers"<<endl;
                cout<<"5. Skirts"<<endl;
                cout<<"6. Shorts"<<endl;
                cout<<"Enter the choice(1-6)"<<endl;
                cin>>c;
                switch(c){
                            case 1: cout<<"How do you wanna filter what you're looking for:"<<endl;
                                    cout<<"1. By Ocassion"<<endl;
                                    cout<<"2. By Style"<<endl;
                                    cout<<"3. By Type"<<endl;
                                    cout<<"Enter the choice(1-3)"<<endl;
                                    cin>>c[1];
                                    switch(c[1]){
                                                case 1: p[1]=in_Ocassion();
                                                        ot_Ocassion();
                                                        break;
                                                case 2: p[2]=in_Style();
                                                        ot_Style();
                                                        break;
                                                case 3: p[3]=in_Type();
                                                        ot_Type();
                                                        break;
                                                default: cout<<"Wrong choice"<<endl;

                                    }
                                    break;
                            case 2: cout<<"What do you wanna buy?"<<endl;
                                    cout<<"1. Tops"<<endl;
                                    cout<<"2. Tshirts"<<endl;
                                    cout<<"3. Shirts"<<endl;
                                    cout<<"4. Partywear"<<endl;
                                    cout<<"Enter the choice(1-4)"<<endl;
                                    cin>>c[2];
                                    switch(c[2]){
                                                case 1: p[4]=in_Tops();
                                                        break;
                                                case 2: p[5]=in_Tshirts();
                                                        break;
                                                case 3: p[6]=in_Shirts();
                                                        break;
                                                case 4: p[7]=in_Partywear();
                                                        break;
                                                default: cout<<"Wrong choice"<<endl;
                                                  }
                                    break;
                            case 3:cout<<"Search by:"<<endl;
                                   cout<<"1. Perfect fit"<<endl;
                                   cout<<"2. Cool collection"<<endl;
                                   cout<<"3. Color pallette"<<endl;
                                   cout<<"4. Rise-filter"<<endl;
                                   cin>>c[3];
                                   switch(c[3]){
                                                case 1: p[8]=in_Pfit();
                                                        break;
                                                case 2: p[9]=in_Cc();
                                                        break;
                                                case 3: p[10]=in_Color();
                                                        break;
                                                case 4: p[11]=in_Rise();
                                                        break;
                                                default: cout<<"Wrong choice"<<endl;
                                                  }
                                    break;
                            case 4: cout<<"Sort by:"<<endl;
                                    cout<<"1. By fit"<<endl;
                                    cout<<"2. Variety of collections"<<endl;
                                    cin>>c[4];
                                    switch(c[4]){
                                                    case 1:p[9]=in_Tfit();
                                                            break;
                                                    case 2:p[10]=in_Tc();
                                                            break;
                                                    default: cout<<"Wrong choice"<<endl;

                                                }
                            case 5: Fltrs();
                                    break;
                            case 6: Fltrs();
                                    break;
                        }                                           //end of switch case


                }                                                   //end of function

void Fltrs(){
                
                cout<<"Enter the size"<<endl;
                cin>>size;
                cout<<"Enter color preference"<<endl;
                cin>>color;
                cout<<"Enter the price appx"<<endl;
                cin>>price;
             }

int in_Ocassion(){
                
                int o;
                cout<<"Toggle list:"<<endl;
                cout<<"1. Everyday"<<endl;
                cout<<"2. Casual"<<endl;
                cout<<"3. Indie+fusion"<<endl;
                cout<<"4. Work"<<endl;
                cout<<"5. Party"<<endl;
                cout<<"6. Jumpsuits& Dungarees:Full length" <<endl;
                cout<<"7. Jumpsuits& Dungarees:Rompers & Playsuits" <<endl;
                cout<<"Enter the choice(1-7)"<<endl;
                cin>>o;
                Fltrs();
                return o;
                            }
    
int in_Style(){
            int a;
            cout<<"Toggle list"<<endl;
            cout<<"1. Lace Dresses"<<endl;
            cout<<"2. Cotton Dresses"<<endl;
            cout<<"3. Maxi Dresses"<<endl;
            cout<<"4. Midi Dresses"<<endl;
            cout<<"5. Short Dresses"<<endl;
            cout<<"6. Floral Dresses"<<endl;
            cout<<"7. Denim Dresses"<<endl;
            cout<<"8. Shimmer and Shine Dresses"<<endl;
            cout<<"9. Stripes & Polkas Dresses"<<endl;
            cout<<"10. Shades of Red Dresses"<<endl;
            cout<<"11. Black Dresses"<<endl;
            cout<<"12. Strappy Dresses"<<endl;
            cout<<"13. Volume Dresses"<<endl;
            cout<<"Enter the choice(1-13)"<<endl;
            cin>>a;
            Fltrs();
            return a;
            }

int in_Type(){
                    int c;
                    cout<<"Toggle list"<<endl;
                    cout<<"1. Empire Dresses"<<endl;
                    cout<<"2. Drop-waist Dresses"<<endl;
                    cout<<"3. A-line Dresses"<<endl;
                    cout<<"4. Body-con Dresses"<<endl;
                    cout<<"5. Fit & Flare Dresses"<<endl;
                    cout<<"6. Pinafore Dresses"<<endl;
                    cout<<"7. Tshirts Dresses"<<endl;
                    cout<<"8. Wrap Dresses"<<endl;
                    cout<<"9. Stripes & Polkas Dresses"<<endl;
                    cout<<"10. Sheath Dresses"<<endl;
                    cout<<"11. Shirt Dresses"<<endl;
                    cout<<"Enter the choice(1-11)"<<endl;
                    cin>>c;
                    Fltrs();
                    return c;
                    }
int in_Tops(){
                    int d;
                    cout<<"Toggle list"<<endl;
                    cout<<"1. Boxy"<<endl;
                    cout<<"2. Solids"<<endl;
                    cout<<"3. Stripes & Checks"<<endl;
                    cout<<"4. Ruffles"<<endl;
                    cout<<"5. Smocked"<<endl;
                    cout<<"6. Florals"<<endl;
                    cout<<"7. Crop Tops"<<endl;
                    cout<<"8. Denims"<<endl;
                    cout<<"9. Ethnic motifs"<<endl;
                    cout<<"10. Color blocking"<<endl;
                    cout<<"Enter the choice(1-10)"<<endl;
                    cin>>a;
                    Fltrs();
                    return a;
                    }

int in_Tshirts(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Printed"<<endl;
                        cout<<"2. Striped"<<endl;
                        cout<<"3. Solids"<<endl;
                        cout<<"4. Polos"<<endl;
                        cout<<"Enter the choice(1-4)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;
                        }
int in_Shirts(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Empire Dresses"<<endl;
                        cout<<"2. Drop-waist Dresses"<<endl;
                        cout<<"3. A-line Dresses"<<endl;
                        cout<<"4. Body-con Dresses"<<endl;
                        cout<<"5. Fit & Flare Dresses"<<endl;
                        cout<<"6. Pinafore Dresses"<<endl;
                        cout<<"Enter the choice(1-6)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;
                    }
int in_Partywear(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Lace & Sheer"<<endl;
                        cout<<"2. Sexy back & cuts"<<endl;
                        cout<<"3. Black Tops"<<endl;
                        cout<<"4. Embellished"<<endl;
                        cout<<"5. Shoulder cuts"<<endl;
                        cout<<"6. Velvets"<<endl;
                        cout<<"7. Metallics & Shimmer"<<endl;
                        cout<<"8. Strappy"<<endl;
                        cout<<"Enter the choice(1-8)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;
                        }
int in_Pfit(){
               int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Super Skinny"<<endl;
                        cout<<"2. Slim fit"<<endl;
                        cout<<"3. Straight fit"<<endl;
                        cout<<"4. Boyfriend Jeans"<<endl;
                        cout<<"5. Bootcut & Flared"<<endl;
                        cout<<"6. Skinny"<<endl;
                        cout<<"7. Jeggings"<<endl;
                        cout<<"Enter the choice(1-7)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;

}
int in_Cc(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Distressed"<<endl;
                        cout<<"2. Slashed Knees"<<endl;
                        cout<<"3. Cropped"<<endl;
                        cout<<"4. High waist"<<endl;
                        cout<<"5. Clean black"<<endl;
                        cout<<"6. Stretchable"<<endl;
                        cout<<"7. Joggers"<<endl;
                        cout<<"8. Mom Jeans"<<endl;
                        cout<<"Enter the choice(1-8)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;
                    }
int in_Rise(){

                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. High"<<endl;
                        cout<<"2. Mid"<<endl;
                        cout<<"3. Rise"<<endl;
                        cout<<"Enter the choice(1-3)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d; 
}
int in_Color(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Dark Blue"<<endl;
                        cout<<"2. Navy Blue"<<endl;
                        cout<<"3. Black"<<endl;
                        cout<<"4. Grey"<<endl;
                        cout<<"5. Charcoal"<<endl;
                        cout<<"6. White"<<endl;
                        cout<<"7. Coloured"<<endl;
                        cout<<"8. Mid-Blue"<<endl;
                        cout<<"9. Fight Blue"<<endl;
                        cout<<"Enter the choice(1-9)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;
                        
}
int in_Tfit(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Skinny fit"<<endl;
                        cout<<"2. Slim fit"<<endl;
                        cout<<"3. Regular fit"<<endl;
                        cout<<"4. Loose fit"<<endl;
                        cout<<"5. Flared"<<endl;
                        cout<<"6. Tapered"<<endl;
                        cout<<"Enter the choice(1-6)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;
}
int in_Tc(){
                        int d;
                        cout<<"Toggle list"<<endl;
                        cout<<"1. Linen"<<endl;
                        cout<<"2. Cotton"<<endl;
                        cout<<"3. Striped"<<endl;
                        cout<<"4. High waist"<<endl;
                        cout<<"5. Cropped"<<endl;
                        cout<<"6. Printed"<<endl;
                        cout<<"Enter the choice(1-6)"<<endl;
                        cin>>d;
                        Fltrs();
                        return d;

}
int ot_Ocassion(){
                    int s[100],t[60];
  switch(p[1]){
            case 1: 
                    s[0]=strcmp(size,"XS");
                    t[0]=strcmp(color,"Black");
                    if((s[0]==1) && (price<=500) && (t[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[1]=strcmp(size,"S");
                    t[1]=strcmp(color,"Black");
                    if((s[1]==1) && (price<=500) && (t[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[2]=strcmp(size,"M");
                    t[2]=strcmp(color,"Black");
                    if((s[2]==1) && (price<=500) && (t[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[3]=strcmp(size,"L");
                    t[3]=strcmp(color,"Black");
                    if((s[3]==1) && (price<=500) && (t[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[4]=strcmp(size,"XL");
                    t[4]=strcmp(color,"Black");
                    if((s[4]==1) && (price<=500) && (t[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s[5]=strcmp(size,"XS");
                    t[5]=strcmp(color,"Black");
                    if((s[5]==1) && ((price>500)&&(price<=1000)) && (t[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[6]=strcmp(size,"S");
                    t[6]=strcmp(color,"Black");
                    if((s[6]==1) && ((price>500)&&(price<=1000)) && (t[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[7]=strcmp(size,"M");
                    t[7]=strcmp(color,"Black");
                    if((s[7]==1) && ((price>500)&&(price<=1000)) && (t[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[8]=strcmp(size,"L");
                    t[8]=strcmp(color,"Black");
                    if((s[8]==1) && ((price>500)&&(price<=1000)) && (t[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[9]=strcmp(size,"XL");
                    t[9]=strcmp(color,"Black");
                    if((s[9]==1) && ((price>500)&&(price<=1000))&& (t[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[10]=strcmp(size,"XS");
                    t[10]=strcmp(color,"Black");
                    if((s[10]==1) && ((price>1000)&&(price<=2000)) && (t[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[11]=strcmp(size,"S");
                    t[11]=strcmp(color,"Black");
                    if((s[11]==1) && ((price>1000)&&(price<=2000)) && (t[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[12]=strcmp(size,"M");
                    t[12]=strcmp(color,"Black");
                    if((s[12]==1) && ((price>1000)&&(price<=2000)) && (t[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[13]=strcmp(size,"L");
                    t[13]=strcmp(color,"Black");
                    if((s[13]==1) && ((price>1000)&&(price<=2000)) && (t[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[14]=strcmp(size,"XL");
                    t[14]=strcmp(color,"Black");
                    if((s[14]==1) && ((price>1000)&&(price<=2000))&& (t[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[15]=strcmp(size,"XS");
                    t[15]=strcmp(color,"Black");
                    if((s[15]==1) && (price>2000) && (t[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[16]=strcmp(size,"S");
                    t[16]=strcmp(color,"Black");
                    if((s[16]==1) && (price>2000) && (t[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[17]=strcmp(size,"M");
                    t[17]=strcmp(color,"Black");
                    if((s[17]==1) && (price>2000) && (t[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[18]=strcmp(size,"L");
                    t[18]=strcmp(color,"Black");
                    if((s[18]==1) && (price>2000) && (t[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[19]=strcmp(size,"XL");
                    t[19]=strcmp(color,"Black");
                    if((s[19]==1) && (price>2000) && (t[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s[20]=strcmp(size,"XS");
                    t[20]=strcmp(color,"Blue");
                    if((s[20]==1) && (price<=500) && (t[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[21]=strcmp(size,"S");
                    t[21]=strcmp(color,"Blue");
                    if((s[21]==1) && (price<=500) && (t[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[22]=strcmp(size,"M");
                    t[22]=strcmp(color,"Blue");
                    if((s[22]==1) && (price<=500) && (t[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[23]=strcmp(size,"L");
                    t[23]=strcmp(color,"Blue");
                    if((s[23]==1) && (price<=500) && (t[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[24]=strcmp(size,"XL");
                    t[24]=strcmp(color,"Blue");
                    if((s[24]==1) && (price<=500) && (t[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s[25]=strcmp(size,"XS");
                    t[25]=strcmp(color,"Blue");
                    if((s[25]==1) && ((price>500)&&(price<=1000)) && (t[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[26]=strcmp(size,"S");
                    t[26]=strcmp(color,"Blue");
                    if((s[26]==1) && ((price>500)&&(price<=1000)) && (t[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[27]=strcmp(size,"M");
                    t[27]=strcmp(color,"Blue");
                    if((s[27]==1) && ((price>500)&&(price<=1000)) && (t[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[28]=strcmp(size,"L");
                    t[28]=strcmp(color,"Blue");
                    if((s[28]==1) && ((price>500)&&(price<=1000)) && (t[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[29]=strcmp(size,"XL");
                    t[29]=strcmp(color,"Blue");
                    if((s[29]==1) && ((price>500)&&(price<=1000))&& (t[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[30]=strcmp(size,"XS");
                    t[30]=strcmp(color,"Blue");
                    if((s[30]==1) && ((price>1000)&&(price<=2000)) && (t[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[31]=strcmp(size,"S");
                    t[31]=strcmp(color,"Blue");
                    if((s[31]==1) && ((price>1000)&&(price<=2000)) && (t[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[32]=strcmp(size,"M");
                    t[32]=strcmp(color,"Blue");
                    if((s[32]==1) && ((price>1000)&&(price<=2000)) && (t[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[33]=strcmp(size,"L");
                    t[33]=strcmp(color,"Blue");
                    if((s[33]==1) && ((price>1000)&&(price<=2000)) && (t[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[34]=strcmp(size,"XL");
                    t[34]=strcmp(color,"Blue");
                    if((s[34]==1) && ((price>1000)&&(price<=2000))&& (t[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[35]=strcmp(size,"XS");
                    t[35]=strcmp(color,"Blue");
                    if((s[35]==1) && (price>2000) && (t[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[36]=strcmp(size,"S");
                    t[36]=strcmp(color,"Blue");
                    if((s[36]==1) && (price>2000) && (t[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[37]=strcmp(size,"M");
                    t[37]=strcmp(color,"Blue");
                    if((s[37]==1) && (price>2000) && (t[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[38]=strcmp(size,"L");
                    t[38]=strcmp(color,"Blue");
                    if((s[38]==1) && (price>2000) && (t[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[39]=strcmp(size,"XL");
                    t[39]=strcmp(color,"Blue");
                    if((s[39]==1) && (price>2000) && (t[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[40]=strcmp(size,"XS");
                    t[40]=strcmp(color,"Red");
                    if((s[40]==1) && (price<=500) && (t[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[41]=strcmp(size,"S");
                    t[41]=strcmp(color,"Red");
                    if((s[41]==1) && (price<=500) && (t[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[42]=strcmp(size,"M");
                    t[42]=strcmp(color,"Red");
                    if((s[42]==1) && (price<=500) && (t[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[43]=strcmp(size,"L");
                    t[43]=strcmp(color,"Red");
                    if((s[43]==1) && (price<=500) && (t[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[44]=strcmp(size,"XL");
                    t[44]=strcmp(color,"Red");
                    if((s[44]==1) && (price<=500) && (t[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s[45]=strcmp(size,"XS");
                    t[45]=strcmp(color,"Red");
                    if((s[45]==1) && ((price>500)&&(price<=1000)) && (t[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[46]=strcmp(size,"S");
                    t[46]=strcmp(color,"Red");
                    if((s[46]==1) && ((price>500)&&(price<=1000)) && (t[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[47]=strcmp(size,"M");
                    t[47]=strcmp(color,"Red");
                    if((s[47]==1) && ((price>500)&&(price<=1000)) && (t[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[48]=strcmp(size,"L");
                    t[48]=strcmp(color,"Red");
                    if((s[48]==1) && ((price>500)&&(price<=1000)) && (t[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[49]=strcmp(size,"XL");
                    t[49]=strcmp(color,"Red");
                    if((s[49]==1) && ((price>500)&&(price<=1000))&& (t[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[50]=strcmp(size,"XS");
                    t[50]=strcmp(color,"Red");
                    if((s[50]==1) && ((price>1000)&&(price<=2000)) && (t[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[51]=strcmp(size,"S");
                    t[51]=strcmp(color,"Red");
                    if((s[51]==1) && ((price>1000)&&(price<=2000)) && (t[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[52]=strcmp(size,"M");
                    t[52]=strcmp(color,"Red");
                    if((s[52]==1) && ((price>1000)&&(price<=2000)) && (t[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[53]=strcmp(size,"L");
                    t[53]=strcmp(color,"Red");
                    if((s[53]==1) && ((price>1000)&&(price<=2000)) && (t[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[54]=strcmp(size,"XL");
                    t[54]=strcmp(color,"Red");
                    if((s[54]==1) && ((price>1000)&&(price<=2000))&& (t[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[55]=strcmp(size,"XS");
                    t[55]=strcmp(color,"Red");
                    if((s[55]==1) && (price>2000) && (t[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[56]=strcmp(size,"S");
                    t[56]=strcmp(color,"Red");
                    if((s[56]==1) && (price>2000) && (t[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[57]=strcmp(size,"M");
                    t[57]=strcmp(color,"Red");
                    if((s[57]==1) && (price>2000) && (t[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[58]=strcmp(size,"L");
                    t[58]=strcmp(color,"Red");
                    if((s[58]==1) && (price>2000) && (t[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[59]=strcmp(size,"XL");
                    t[59]=strcmp(color,"Black");
                    if((s[59]==1) && (price>2000) && (t[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s[60]=strcmp(size,"XS");
                    
                    if((s[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[61]=strcmp(size,"S");
                    
                    if((s[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[62]=strcmp(size,"M");
                    
                    if((s[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[63]=strcmp(size,"L");
                    
                    if((s[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[64]=strcmp(size,"XL");
                    
                    if((s[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s[65]=strcmp(size,"XS");
                   
                    if((s[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[66]=strcmp(size,"S");
                    
                    if((s[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[67]=strcmp(size,"M");
                    
                    if((s[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[68]=strcmp(size,"L");
                   
                    if((s[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[69]=strcmp(size,"XL");
                    
                    if((s[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[70]=strcmp(size,"XS");
                    
                    if((s[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[71]=strcmp(size,"S");
                    
                    if((s[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[72]=strcmp(size,"M");
                    
                    if((s[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[73]=strcmp(size,"L");
                    
                    if((s[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[74]=strcmp(size,"XL");
                    
                    if((s[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[75]=strcmp(size,"XS");
                    
                    if((s[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[76]=strcmp(size,"S");
                    
                    if((s[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s[77]=strcmp(size,"M");
                    
                    if((s[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s[78]=strcmp(size,"L");
                    
                    if((s[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s[79]=strcmp(size,"XL");
                    
                    if((s[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    break;
       case 2:      int s1[100],t1[60];
                    s1[0]=strcmp(size,"XS");
                    t1[0]=strcmp(color,"Black");
                    if((s1[0]==1) && (price<=500) && (t1[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[1]=strcmp(size,"S");
                    t1[1]=strcmp(color,"Black");
                    if((s1[1]==1) && (price<=500) && (t1[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[2]=strcmp(size,"M");
                    t1[2]=strcmp(color,"Black");
                    if((s1[2]==1) && (price<=500) && (t1[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[3]=strcmp(size,"L");
                    t1[3]=strcmp(color,"Black");
                    if((s1[3]==1) && (price<=500) && (t1[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[4]=strcmp(size,"XL");
                    t1[4]=strcmp(color,"Black");
                    if((s1[4]==1) && (price<=500) && (t1[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s1[5]=strcmp(size,"XS");
                    t1[5]=strcmp(color,"Black");
                    if((s1[5]==1) && ((price>500)&&(price<=1000)) && (t1[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[6]=strcmp(size,"S");
                    t1[6]=strcmp(color,"Black");
                    if((s1[6]==1) && ((price>500)&&(price<=1000)) && (t1[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[7]=strcmp(size,"M");
                    t1[7]=strcmp(color,"Black");
                    if((s1[7]==1) && ((price>500)&&(price<=1000)) && (t1[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[8]=strcmp(size,"L");
                    t1[8]=strcmp(color,"Black");
                    if((s1[8]==1) && ((price>500)&&(price<=1000)) && (t1[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[9]=strcmp(size,"XL");
                    t1[9]=strcmp(color,"Black");
                    if((s1[9]==1) && ((price>500)&&(price<=1000))&& (t1[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[10]=strcmp(size,"XS");
                    t1[10]=strcmp(color,"Black");
                    if((s1[10]==1) && ((price>1000)&&(price<=2000)) && (t1[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[11]=strcmp(size,"S");
                    t1[11]=strcmp(color,"Black");
                    if((s1[11]==1) && ((price>1000)&&(price<=2000)) && (t1[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[12]=strcmp(size,"M");
                    t1[12]=strcmp(color,"Black");
                    if((s1[12]==1) && ((price>1000)&&(price<=2000)) && (t1[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[13]=strcmp(size,"L");
                    t1[13]=strcmp(color,"Black");
                    if((s1[13]==1) && ((price>1000)&&(price<=2000)) && (t1[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[14]=strcmp(size,"XL");
                    t1[14]=strcmp(color,"Black");
                    if((s1[14]==1) && ((price>1000)&&(price<=2000))&& (t1[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[15]=strcmp(size,"XS");
                    t1[15]=strcmp(color,"Black");
                    if((s1[15]==1) && (price>2000) && (t1[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[16]=strcmp(size,"S");
                    t1[16]=strcmp(color,"Black");
                    if((s1[16]==1) && (price>2000) && (t1[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[17]=strcmp(size,"M");
                    t1[17]=strcmp(color,"Black");
                    if((s1[17]==1) && (price>2000) && (t1[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[18]=strcmp(size,"L");
                    t1[18]=strcmp(color,"Black");
                    if((s1[18]==1) && (price>2000) && (t1[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[19]=strcmp(size,"XL");
                    t1[19]=strcmp(color,"Black");
                    if((s1[19]==1) && (price>2000) && (t1[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s1[20]=strcmp(size,"XS");
                    t1[20]=strcmp(color,"Blue");
                    if((s1[20]==1) && (price<=500) && (t1[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[21]=strcmp(size,"S");
                    t1[21]=strcmp(color,"Blue");
                    if((s1[21]==1) && (price<=500) && (t1[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[22]=strcmp(size,"M");
                    t1[22]=strcmp(color,"Blue");
                    if((s1[22]==1) && (price<=500) && (t1[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[23]=strcmp(size,"L");
                    t1[23]=strcmp(color,"Blue");
                    if((s1[23]==1) && (price<=500) && (t1[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[24]=strcmp(size,"XL");
                    t1[24]=strcmp(color,"Blue");
                    if((s1[24]==1) && (price<=500) && (t1[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s1[25]=strcmp(size,"XS");
                    t1[25]=strcmp(color,"Blue");
                    if((s1[25]==1) && ((price>500)&&(price<=1000)) && (t1[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[26]=strcmp(size,"S");
                    t1[26]=strcmp(color,"Blue");
                    if((s1[26]==1) && ((price>500)&&(price<=1000)) && (t1[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[27]=strcmp(size,"M");
                    t1[27]=strcmp(color,"Blue");
                    if((s1[27]==1) && ((price>500)&&(price<=1000)) && (t1[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[28]=strcmp(size,"L");
                    t1[28]=strcmp(color,"Blue");
                    if((s1[28]==1) && ((price>500)&&(price<=1000)) && (t1[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[29]=strcmp(size,"XL");
                    t1[29]=strcmp(color,"Blue");
                    if((s1[29]==1) && ((price>500)&&(price<=1000))&& (t1[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[30]=strcmp(size,"XS");
                    t1[30]=strcmp(color,"Blue");
                    if((s1[30]==1) && ((price>1000)&&(price<=2000)) && (t1[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[31]=strcmp(size,"S");
                    t1[31]=strcmp(color,"Blue");
                    if((s1[31]==1) && ((price>1000)&&(price<=2000)) && (t1[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[32]=strcmp(size,"M");
                    t1[32]=strcmp(color,"Blue");
                    if((s1[32]==1) && ((price>1000)&&(price<=2000)) && (t1[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[33]=strcmp(size,"L");
                    t1[33]=strcmp(color,"Blue");
                    if((s1[33]==1) && ((price>1000)&&(price<=2000)) && (t1[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[34]=strcmp(size,"XL");
                    t1[34]=strcmp(color,"Blue");
                    if((s1[34]==1) && ((price>1000)&&(price<=2000))&& (t1[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[35]=strcmp(size,"XS");
                    t1[35]=strcmp(color,"Blue");
                    if((s1[35]==1) && (price>2000) && (t1[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[36]=strcmp(size,"S");
                    t1[36]=strcmp(color,"Blue");
                    if((s1[36]==1) && (price>2000) && (t1[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[37]=strcmp(size,"M");
                    t1[37]=strcmp(color,"Blue");
                    if((s1[37]==1) && (price>2000) && (t1[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[38]=strcmp(size,"L");
                    t1[38]=strcmp(color,"Blue");
                    if((s1[38]==1) && (price>2000) && (t1[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[39]=strcmp(size,"XL");
                    t1[39]=strcmp(color,"Blue");
                    if((s1[39]==1) && (price>2000) && (t1[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[40]=strcmp(size,"XS");
                    t1[40]=strcmp(color,"Red");
                    if((s1[40]==1) && (price<=500) && (t1[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[41]=strcmp(size,"S");
                    t1[41]=strcmp(color,"Red");
                    if((s1[41]==1) && (price<=500) && (t1[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[42]=strcmp(size,"M");
                    t1[42]=strcmp(color,"Red");
                    if((s1[42]==1) && (price<=500) && (t1[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[43]=strcmp(size,"L");
                    t1[43]=strcmp(color,"Red");
                    if((s1[43]==1) && (price<=500) && (t1[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[44]=strcmp(size,"XL");
                    t1[44]=strcmp(color,"Red");
                    if((s1[44]==1) && (price<=500) && (t1[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s1[45]=strcmp(size,"XS");
                    t1[45]=strcmp(color,"Red");
                    if((s1[45]==1) && ((price>500)&&(price<=1000)) && (t1[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[46]=strcmp(size,"S");
                    t1[46]=strcmp(color,"Red");
                    if((s1[46]==1) && ((price>500)&&(price<=1000)) && (t1[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[47]=strcmp(size,"M");
                    t1[47]=strcmp(color,"Red");
                    if((s1[47]==1) && ((price>500)&&(price<=1000)) && (t1[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[48]=strcmp(size,"L");
                    t1[48]=strcmp(color,"Red");
                    if((s1[48]==1) && ((price>500)&&(price<=1000)) && (t1[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[49]=strcmp(size,"XL");
                    t1[49]=strcmp(color,"Red");
                    if((s1[49]==1) && ((price>500)&&(price<=1000))&& (t1[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[50]=strcmp(size,"XS");
                    t1[50]=strcmp(color,"Red");
                    if((s1[50]==1) && ((price>1000)&&(price<=2000)) && (t1[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[51]=strcmp(size,"S");
                    t1[51]=strcmp(color,"Red");
                    if((s1[51]==1) && ((price>1000)&&(price<=2000)) && (t1[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[52]=strcmp(size,"M");
                    t1[52]=strcmp(color,"Red");
                    if((s1[52]==1) && ((price>1000)&&(price<=2000)) && (t1[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[53]=strcmp(size,"L");
                    t1[53]=strcmp(color,"Red");
                    if((s1[53]==1) && ((price>1000)&&(price<=2000)) && (t1[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[54]=strcmp(size,"XL");
                    t1[54]=strcmp(color,"Red");
                    if((s1[54]==1) && ((price>1000)&&(price<=2000))&& (t1[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[55]=strcmp(size,"XS");
                    t1[55]=strcmp(color,"Red");
                    if((s1[55]==1) && (price>2000) && (t1[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[56]=strcmp(size,"S");
                    t1[56]=strcmp(color,"Red");
                    if((s1[56]==1) && (price>2000) && (t1[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[57]=strcmp(size,"M");
                    t1[57]=strcmp(color,"Red");
                    if((s1[57]==1) && (price>2000) && (t1[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[58]=strcmp(size,"L");
                    t1[58]=strcmp(color,"Red");
                    if((s1[58]==1) && (price>2000) && (t1[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[59]=strcmp(size,"XL");
                    t1[59]=strcmp(color,"Black");
                    if((s1[59]==1) && (price>2000) && (t1[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s1[60]=strcmp(size,"XS");
                    
                    if((s1[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[61]=strcmp(size,"S");
                    
                    if((s1[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[62]=strcmp(size,"M");
                    
                    if((s1[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[63]=strcmp(size,"L");
                    
                    if((s1[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[64]=strcmp(size,"XL");
                    
                    if((s1[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s1[65]=strcmp(size,"XS");
                   
                    if((s1[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[66]=strcmp(size,"S");
                    
                    if((s1[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[67]=strcmp(size,"M");
                    
                    if((s1[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[68]=strcmp(size,"L");
                   
                    if((s1[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[69]=strcmp(size,"XL");
                    
                    if((s1[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[70]=strcmp(size,"XS");
                    
                    if((s1[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[71]=strcmp(size,"S");
                    
                    if((s1[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[72]=strcmp(size,"M");
                    
                    if((s1[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[73]=strcmp(size,"L");
                    
                    if((s1[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[74]=strcmp(size,"XL");
                    
                    if((s1[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[75]=strcmp(size,"XS");
                    
                    if((s1[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[76]=strcmp(size,"S");
                    
                    if((s1[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s1[77]=strcmp(size,"M");
                    
                    if((s1[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s1[78]=strcmp(size,"L");
                    
                    if((s1[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s1[79]=strcmp(size,"XL");
                    
                    if((s1[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
        case 3:     int s2[100],t2[60];
                    s2[0]=strcmp(size,"XS");
                    t2[0]=strcmp(color,"Black");
                    if((s2[0]==1) && (price<=500) && (t2[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[1]=strcmp(size,"S");
                    t2[1]=strcmp(color,"Black");
                    if((s2[1]==1) && (price<=500) && (t2[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[2]=strcmp(size,"M");
                    t2[2]=strcmp(color,"Black");
                    if((s2[2]==1) && (price<=500) && (t2[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[3]=strcmp(size,"L");
                    t2[3]=strcmp(color,"Black");
                    if((s2[3]==1) && (price<=500) && (t2[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[4]=strcmp(size,"XL");
                    t2[4]=strcmp(color,"Black");
                    if((s2[4]==1) && (price<=500) && (t2[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s2[5]=strcmp(size,"XS");
                    t2[5]=strcmp(color,"Black");
                    if((s2[5]==1) && ((price>500)&&(price<=1000)) && (t2[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[6]=strcmp(size,"S");
                    t2[6]=strcmp(color,"Black");
                    if((s2[6]==1) && ((price>500)&&(price<=1000)) && (t2[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[7]=strcmp(size,"M");
                    t2[7]=strcmp(color,"Black");
                    if((s2[7]==1) && ((price>500)&&(price<=1000)) && (t2[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[8]=strcmp(size,"L");
                    t2[8]=strcmp(color,"Black");
                    if((s2[8]==1) && ((price>500)&&(price<=1000)) && (t2[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[9]=strcmp(size,"XL");
                    t2[9]=strcmp(color,"Black");
                    if((s2[9]==1) && ((price>500)&&(price<=1000))&& (t2[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[10]=strcmp(size,"XS");
                    t2[10]=strcmp(color,"Black");
                    if((s2[10]==1) && ((price>1000)&&(price<=2000)) && (t2[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[11]=strcmp(size,"S");
                    t2[11]=strcmp(color,"Black");
                    if((s2[11]==1) && ((price>1000)&&(price<=2000)) && (t2[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[12]=strcmp(size,"M");
                    t2[12]=strcmp(color,"Black");
                    if((s2[12]==1) && ((price>1000)&&(price<=2000)) && (t2[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[13]=strcmp(size,"L");
                    t2[13]=strcmp(color,"Black");
                    if((s2[13]==1) && ((price>1000)&&(price<=2000)) && (t2[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[14]=strcmp(size,"XL");
                    t2[14]=strcmp(color,"Black");
                    if((s2[14]==1) && ((price>1000)&&(price<=2000))&& (t2[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[15]=strcmp(size,"XS");
                    t2[15]=strcmp(color,"Black");
                    if((s2[15]==1) && (price>2000) && (t2[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[16]=strcmp(size,"S");
                    t2[16]=strcmp(color,"Black");
                    if((s2[16]==1) && (price>2000) && (t2[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[17]=strcmp(size,"M");
                    t2[17]=strcmp(color,"Black");
                    if((s2[17]==1) && (price>2000) && (t2[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[18]=strcmp(size,"L");
                    t2[18]=strcmp(color,"Black");
                    if((s2[18]==1) && (price>2000) && (t2[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[19]=strcmp(size,"XL");
                    t2[19]=strcmp(color,"Black");
                    if((s2[19]==1) && (price>2000) && (t2[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s2[20]=strcmp(size,"XS");
                    t2[20]=strcmp(color,"Blue");
                    if((s2[20]==1) && (price<=500) && (t2[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[21]=strcmp(size,"S");
                    t2[21]=strcmp(color,"Blue");
                    if((s2[21]==1) && (price<=500) && (t2[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[22]=strcmp(size,"M");
                    t2[22]=strcmp(color,"Blue");
                    if((s2[22]==1) && (price<=500) && (t2[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[23]=strcmp(size,"L");
                    t2[23]=strcmp(color,"Blue");
                    if((s2[23]==1) && (price<=500) && (t2[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[24]=strcmp(size,"XL");
                    t2[24]=strcmp(color,"Blue");
                    if((s2[24]==1) && (price<=500) && (t2[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s2[25]=strcmp(size,"XS");
                    t2[25]=strcmp(color,"Blue");
                    if((s2[25]==1) && ((price>500)&&(price<=1000)) && (t2[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[26]=strcmp(size,"S");
                    t2[26]=strcmp(color,"Blue");
                    if((s2[26]==1) && ((price>500)&&(price<=1000)) && (t2[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[27]=strcmp(size,"M");
                    t2[27]=strcmp(color,"Blue");
                    if((s2[27]==1) && ((price>500)&&(price<=1000)) && (t2[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[28]=strcmp(size,"L");
                    t2[28]=strcmp(color,"Blue");
                    if((s2[28]==1) && ((price>500)&&(price<=1000)) && (t2[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[29]=strcmp(size,"XL");
                    t2[29]=strcmp(color,"Blue");
                    if((s2[29]==1) && ((price>500)&&(price<=1000))&& (t2[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[30]=strcmp(size,"XS");
                    t2[30]=strcmp(color,"Blue");
                    if((s2[30]==1) && ((price>1000)&&(price<=2000)) && (t2[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[31]=strcmp(size,"S");
                    t2[31]=strcmp(color,"Blue");
                    if((s2[31]==1) && ((price>1000)&&(price<=2000)) && (t2[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[32]=strcmp(size,"M");
                    t2[32]=strcmp(color,"Blue");
                    if((s2[32]==1) && ((price>1000)&&(price<=2000)) && (t2[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[33]=strcmp(size,"L");
                    t2[33]=strcmp(color,"Blue");
                    if((s2[33]==1) && ((price>1000)&&(price<=2000)) && (t2[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[34]=strcmp(size,"XL");
                    t2[34]=strcmp(color,"Blue");
                    if((s2[34]==1) && ((price>1000)&&(price<=2000))&& (t2[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[35]=strcmp(size,"XS");
                    t2[35]=strcmp(color,"Blue");
                    if((s2[35]==1) && (price>2000) && (t2[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[36]=strcmp(size,"S");
                    t2[36]=strcmp(color,"Blue");
                    if((s2[36]==1) && (price>2000) && (t2[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[37]=strcmp(size,"M");
                    t2[37]=strcmp(color,"Blue");
                    if((s2[37]==1) && (price>2000) && (t2[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[38]=strcmp(size,"L");
                    t2[38]=strcmp(color,"Blue");
                    if((s2[38]==1) && (price>2000) && (t2[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[39]=strcmp(size,"XL");
                    t2[39]=strcmp(color,"Blue");
                    if((s2[39]==1) && (price>2000) && (t2[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[40]=strcmp(size,"XS");
                    t2[40]=strcmp(color,"Red");
                    if((s2[40]==1) && (price<=500) && (t2[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[41]=strcmp(size,"S");
                    t2[41]=strcmp(color,"Red");
                    if((s2[41]==1) && (price<=500) && (t2[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[42]=strcmp(size,"M");
                    t2[42]=strcmp(color,"Red");
                    if((s2[42]==1) && (price<=500) && (t2[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[43]=strcmp(size,"L");
                    t2[43]=strcmp(color,"Red");
                    if((s2[43]==1) && (price<=500) && (t2[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[44]=strcmp(size,"XL");
                    t2[44]=strcmp(color,"Red");
                    if((s2[44]==1) && (price<=500) && (t2[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s2[45]=strcmp(size,"XS");
                    t2[45]=strcmp(color,"Red");
                    if((s2[45]==1) && ((price>500)&&(price<=1000)) && (t2[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[46]=strcmp(size,"S");
                    t2[46]=strcmp(color,"Red");
                    if((s2[46]==1) && ((price>500)&&(price<=1000)) && (t2[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[47]=strcmp(size,"M");
                    t2[47]=strcmp(color,"Red");
                    if((s2[47]==1) && ((price>500)&&(price<=1000)) && (t2[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[48]=strcmp(size,"L");
                    t2[48]=strcmp(color,"Red");
                    if((s2[48]==1) && ((price>500)&&(price<=1000)) && (t2[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[49]=strcmp(size,"XL");
                    t2[49]=strcmp(color,"Red");
                    if((s2[49]==1) && ((price>500)&&(price<=1000))&& (t2[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[50]=strcmp(size,"XS");
                    t2[50]=strcmp(color,"Red");
                    if((s2[50]==1) && ((price>1000)&&(price<=2000)) && (t2[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[51]=strcmp(size,"S");
                    t2[51]=strcmp(color,"Red");
                    if((s2[51]==1) && ((price>1000)&&(price<=2000)) && (t2[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[52]=strcmp(size,"M");
                    t2[52]=strcmp(color,"Red");
                    if((s2[52]==1) && ((price>1000)&&(price<=2000)) && (t2[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[53]=strcmp(size,"L");
                    t2[53]=strcmp(color,"Red");
                    if((s2[53]==1) && ((price>1000)&&(price<=2000)) && (t2[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[54]=strcmp(size,"XL");
                    t2[54]=strcmp(color,"Red");
                    if((s2[54]==1) && ((price>1000)&&(price<=2000))&& (t2[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[55]=strcmp(size,"XS");
                    t2[55]=strcmp(color,"Red");
                    if((s2[55]==1) && (price>2000) && (t2[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[56]=strcmp(size,"S");
                    t2[56]=strcmp(color,"Red");
                    if((s2[56]==1) && (price>2000) && (t2[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[57]=strcmp(size,"M");
                    t2[57]=strcmp(color,"Red");
                    if((s2[57]==1) && (price>2000) && (t2[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[58]=strcmp(size,"L");
                    t2[58]=strcmp(color,"Red");
                    if((s2[58]==1) && (price>2000) && (t2[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[59]=strcmp(size,"XL");
                    t2[59]=strcmp(color,"Black");
                    if((s2[59]==1) && (price>2000) && (t2[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s2[60]=strcmp(size,"XS");
                    
                    if((s2[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[61]=strcmp(size,"S");
                    
                    if((s2[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[62]=strcmp(size,"M");
                    
                    if((s2[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[63]=strcmp(size,"L");
                    
                    if((s2[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[64]=strcmp(size,"XL");
                    
                    if((s2[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s2[65]=strcmp(size,"XS");
                   
                    if((s2[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[66]=strcmp(size,"S");
                    
                    if((s2[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[67]=strcmp(size,"M");
                    
                    if((s2[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[68]=strcmp(size,"L");
                   
                    if((s2[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[69]=strcmp(size,"XL");
                    
                    if((s2[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[70]=strcmp(size,"XS");
                    
                    if((s2[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[71]=strcmp(size,"S");
                    
                    if((s2[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[72]=strcmp(size,"M");
                    
                    if((s2[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[73]=strcmp(size,"L");
                    
                    if((s2[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[74]=strcmp(size,"XL");
                    
                    if((s2[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[75]=strcmp(size,"XS");
                    
                    if((s2[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[76]=strcmp(size,"S");
                    
                    if((s2[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s2[77]=strcmp(size,"M");
                    
                    if((s2[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s2[78]=strcmp(size,"L");
                    
                    if((s2[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s2[79]=strcmp(size,"XL");
                    
                    if((s2[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     break;
        case 3:     int s3[100],t3[60];
                    s3[0]=strcmp(size,"XS");
                    t3[0]=strcmp(color,"Black");
                    if((s3[0]==1) && (price<=500) && (t3[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[1]=strcmp(size,"S");
                    t3[1]=strcmp(color,"Black");
                    if((s3[1]==1) && (price<=500) && (t3[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[2]=strcmp(size,"M");
                    t3[2]=strcmp(color,"Black");
                    if((s3[2]==1) && (price<=500) && (t3[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[3]=strcmp(size,"L");
                    t3[3]=strcmp(color,"Black");
                    if((s3[3]==1) && (price<=500) && (t3[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[4]=strcmp(size,"XL");
                    t3[4]=strcmp(color,"Black");
                    if((s3[4]==1) && (price<=500) && (t3[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s3[5]=strcmp(size,"XS");
                    t3[5]=strcmp(color,"Black");
                    if((s3[5]==1) && ((price>500)&&(price<=1000)) && (t3[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[6]=strcmp(size,"S");
                    t3[6]=strcmp(color,"Black");
                    if((s3[6]==1) && ((price>500)&&(price<=1000)) && (t3[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[7]=strcmp(size,"M");
                    t3[7]=strcmp(color,"Black");
                    if((s3[7]==1) && ((price>500)&&(price<=1000)) && (t3[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[8]=strcmp(size,"L");
                    t3[8]=strcmp(color,"Black");
                    if((s3[8]==1) && ((price>500)&&(price<=1000)) && (t3[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[9]=strcmp(size,"XL");
                    t3[9]=strcmp(color,"Black");
                    if((s3[9]==1) && ((price>500)&&(price<=1000))&& (t3[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[10]=strcmp(size,"XS");
                    t3[10]=strcmp(color,"Black");
                    if((s3[10]==1) && ((price>1000)&&(price<=2000)) && (t3[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[11]=strcmp(size,"S");
                    t3[11]=strcmp(color,"Black");
                    if((s3[11]==1) && ((price>1000)&&(price<=2000)) && (t3[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[12]=strcmp(size,"M");
                    t3[12]=strcmp(color,"Black");
                    if((s3[12]==1) && ((price>1000)&&(price<=2000)) && (t3[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[13]=strcmp(size,"L");
                    t3[13]=strcmp(color,"Black");
                    if((s3[13]==1) && ((price>1000)&&(price<=2000)) && (t3[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[14]=strcmp(size,"XL");
                    t3[14]=strcmp(color,"Black");
                    if((s3[14]==1) && ((price>1000)&&(price<=2000))&& (t3[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[15]=strcmp(size,"XS");
                    t3[15]=strcmp(color,"Black");
                    if((s3[15]==1) && (price>2000) && (t3[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[16]=strcmp(size,"S");
                    t3[16]=strcmp(color,"Black");
                    if((s3[16]==1) && (price>2000) && (t3[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[17]=strcmp(size,"M");
                    t3[17]=strcmp(color,"Black");
                    if((s3[17]==1) && (price>2000) && (t3[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[18]=strcmp(size,"L");
                    t3[18]=strcmp(color,"Black");
                    if((s3[18]==1) && (price>2000) && (t3[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[19]=strcmp(size,"XL");
                    t3[19]=strcmp(color,"Black");
                    if((s3[19]==1) && (price>2000) && (t3[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s3[20]=strcmp(size,"XS");
                    t3[20]=strcmp(color,"Blue");
                    if((s3[20]==1) && (price<=500) && (t3[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[21]=strcmp(size,"S");
                    t3[21]=strcmp(color,"Blue");
                    if((s3[21]==1) && (price<=500) && (t3[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[22]=strcmp(size,"M");
                    t3[22]=strcmp(color,"Blue");
                    if((s3[22]==1) && (price<=500) && (t3[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[23]=strcmp(size,"L");
                    t3[23]=strcmp(color,"Blue");
                    if((s3[23]==1) && (price<=500) && (t3[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[24]=strcmp(size,"XL");
                    t3[24]=strcmp(color,"Blue");
                    if((s3[24]==1) && (price<=500) && (t3[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s3[25]=strcmp(size,"XS");
                    t3[25]=strcmp(color,"Blue");
                    if((s3[25]==1) && ((price>500)&&(price<=1000)) && (t3[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[26]=strcmp(size,"S");
                    t3[26]=strcmp(color,"Blue");
                    if((s3[26]==1) && ((price>500)&&(price<=1000)) && (t3[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[27]=strcmp(size,"M");
                    t3[27]=strcmp(color,"Blue");
                    if((s3[27]==1) && ((price>500)&&(price<=1000)) && (t3[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[28]=strcmp(size,"L");
                    t3[28]=strcmp(color,"Blue");
                    if((s3[28]==1) && ((price>500)&&(price<=1000)) && (t3[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[29]=strcmp(size,"XL");
                    t3[29]=strcmp(color,"Blue");
                    if((s3[29]==1) && ((price>500)&&(price<=1000))&& (t3[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[30]=strcmp(size,"XS");
                    t3[30]=strcmp(color,"Blue");
                    if((s3[30]==1) && ((price>1000)&&(price<=2000)) && (t3[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[31]=strcmp(size,"S");
                    t3[31]=strcmp(color,"Blue");
                    if((s3[31]==1) && ((price>1000)&&(price<=2000)) && (t3[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[32]=strcmp(size,"M");
                    t3[32]=strcmp(color,"Blue");
                    if((s3[32]==1) && ((price>1000)&&(price<=2000)) && (t3[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[33]=strcmp(size,"L");
                    t3[33]=strcmp(color,"Blue");
                    if((s3[33]==1) && ((price>1000)&&(price<=2000)) && (t3[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[34]=strcmp(size,"XL");
                    t3[34]=strcmp(color,"Blue");
                    if((s3[34]==1) && ((price>1000)&&(price<=2000))&& (t3[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[35]=strcmp(size,"XS");
                    t3[35]=strcmp(color,"Blue");
                    if((s3[35]==1) && (price>2000) && (t3[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[36]=strcmp(size,"S");
                    t3[36]=strcmp(color,"Blue");
                    if((s3[36]==1) && (price>2000) && (t3[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[37]=strcmp(size,"M");
                    t3[37]=strcmp(color,"Blue");
                    if((s3[37]==1) && (price>2000) && (t3[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[38]=strcmp(size,"L");
                    t3[38]=strcmp(color,"Blue");
                    if((s3[38]==1) && (price>2000) && (t3[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[39]=strcmp(size,"XL");
                    t3[39]=strcmp(color,"Blue");
                    if((s3[39]==1) && (price>2000) && (t3[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[40]=strcmp(size,"XS");
                    t3[40]=strcmp(color,"Red");
                    if((s3[40]==1) && (price<=500) && (t3[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[41]=strcmp(size,"S");
                    t3[41]=strcmp(color,"Red");
                    if((s3[41]==1) && (price<=500) && (t3[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[42]=strcmp(size,"M");
                    t3[42]=strcmp(color,"Red");
                    if((s3[42]==1) && (price<=500) && (t3[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[43]=strcmp(size,"L");
                    t3[43]=strcmp(color,"Red");
                    if((s3[43]==1) && (price<=500) && (t3[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[44]=strcmp(size,"XL");
                    t3[44]=strcmp(color,"Red");
                    if((s3[44]==1) && (price<=500) && (t3[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s3[45]=strcmp(size,"XS");
                    t3[45]=strcmp(color,"Red");
                    if((s3[45]==1) && ((price>500)&&(price<=1000)) && (t3[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[46]=strcmp(size,"S");
                    t3[46]=strcmp(color,"Red");
                    if((s3[46]==1) && ((price>500)&&(price<=1000)) && (t3[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[47]=strcmp(size,"M");
                    t3[47]=strcmp(color,"Red");
                    if((s3[47]==1) && ((price>500)&&(price<=1000)) && (t3[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[48]=strcmp(size,"L");
                    t3[48]=strcmp(color,"Red");
                    if((s3[48]==1) && ((price>500)&&(price<=1000)) && (t3[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[49]=strcmp(size,"XL");
                    t3[49]=strcmp(color,"Red");
                    if((s3[49]==1) && ((price>500)&&(price<=1000))&& (t3[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[50]=strcmp(size,"XS");
                    t3[50]=strcmp(color,"Red");
                    if((s3[50]==1) && ((price>1000)&&(price<=2000)) && (t3[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[51]=strcmp(size,"S");
                    t3[51]=strcmp(color,"Red");
                    if((s3[51]==1) && ((price>1000)&&(price<=2000)) && (t3[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[52]=strcmp(size,"M");
                    t3[52]=strcmp(color,"Red");
                    if((s3[52]==1) && ((price>1000)&&(price<=2000)) && (t3[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[53]=strcmp(size,"L");
                    t3[53]=strcmp(color,"Red");
                    if((s3[53]==1) && ((price>1000)&&(price<=2000)) && (t3[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[54]=strcmp(size,"XL");
                    t3[54]=strcmp(color,"Red");
                    if((s3[54]==1) && ((price>1000)&&(price<=2000))&& (t3[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[55]=strcmp(size,"XS");
                    t3[55]=strcmp(color,"Red");
                    if((s3[55]==1) && (price>2000) && (t3[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[56]=strcmp(size,"S");
                    t3[56]=strcmp(color,"Red");
                    if((s3[56]==1) && (price>2000) && (t3[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[57]=strcmp(size,"M");
                    t3[57]=strcmp(color,"Red");
                    if((s3[57]==1) && (price>2000) && (t3[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[58]=strcmp(size,"L");
                    t3[58]=strcmp(color,"Red");
                    if((s3[58]==1) && (price>2000) && (t3[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[59]=strcmp(size,"XL");
                    t3[59]=strcmp(color,"Black");
                    if((s3[59]==1) && (price>2000) && (t3[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s3[60]=strcmp(size,"XS");
                    
                    if((s3[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[61]=strcmp(size,"S");
                    
                    if((s3[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[62]=strcmp(size,"M");
                    
                    if((s3[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[63]=strcmp(size,"L");
                    
                    if((s3[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[64]=strcmp(size,"XL");
                    
                    if((s3[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s3[65]=strcmp(size,"XS");
                   
                    if((s3[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[66]=strcmp(size,"S");
                    
                    if((s3[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[67]=strcmp(size,"M");
                    
                    if((s3[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[68]=strcmp(size,"L");
                   
                    if((s3[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[69]=strcmp(size,"XL");
                    
                    if((s3[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[70]=strcmp(size,"XS");
                    
                    if((s3[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[71]=strcmp(size,"S");
                    
                    if((s3[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[72]=strcmp(size,"M");
                    
                    if((s3[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[73]=strcmp(size,"L");
                    
                    if((s3[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[74]=strcmp(size,"XL");
                    
                    if((s3[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[75]=strcmp(size,"XS");
                    
                    if((s3[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[76]=strcmp(size,"S");
                    
                    if((s3[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s3[77]=strcmp(size,"M");
                    
                    if((s3[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s3[78]=strcmp(size,"L");
                    
                    if((s3[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s3[79]=strcmp(size,"XL");
                    
                    if((s3[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     break;
            case 4: int s4[100],t4[60];
                    s4[0]=strcmp(size,"XS");
                    t4[0]=strcmp(color,"Black");
                    if((s4[0]==1) && (price<=500) && (t4[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[1]=strcmp(size,"S");
                    t4[1]=strcmp(color,"Black");
                    if((s4[1]==1) && (price<=500) && (t4[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[2]=strcmp(size,"M");
                    t4[2]=strcmp(color,"Black");
                    if((s4[2]==1) && (price<=500) && (t4[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[3]=strcmp(size,"L");
                    t4[3]=strcmp(color,"Black");
                    if((s4[3]==1) && (price<=500) && (t4[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[4]=strcmp(size,"XL");
                    t4[4]=strcmp(color,"Black");
                    if((s4[4]==1) && (price<=500) && (t4[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s4[5]=strcmp(size,"XS");
                    t4[5]=strcmp(color,"Black");
                    if((s4[5]==1) && ((price>500)&&(price<=1000)) && (t4[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[6]=strcmp(size,"S");
                    t4[6]=strcmp(color,"Black");
                    if((s4[6]==1) && ((price>500)&&(price<=1000)) && (t4[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[7]=strcmp(size,"M");
                    t4[7]=strcmp(color,"Black");
                    if((s4[7]==1) && ((price>500)&&(price<=1000)) && (t4[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[8]=strcmp(size,"L");
                    t4[8]=strcmp(color,"Black");
                    if((s4[8]==1) && ((price>500)&&(price<=1000)) && (t4[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[9]=strcmp(size,"XL");
                    t4[9]=strcmp(color,"Black");
                    if((s4[9]==1) && ((price>500)&&(price<=1000))&& (t4[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[10]=strcmp(size,"XS");
                    t4[10]=strcmp(color,"Black");
                    if((s4[10]==1) && ((price>1000)&&(price<=2000)) && (t4[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[11]=strcmp(size,"S");
                    t4[11]=strcmp(color,"Black");
                    if((s4[11]==1) && ((price>1000)&&(price<=2000)) && (t4[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[12]=strcmp(size,"M");
                    t4[12]=strcmp(color,"Black");
                    if((s4[12]==1) && ((price>1000)&&(price<=2000)) && (t4[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[13]=strcmp(size,"L");
                    t4[13]=strcmp(color,"Black");
                    if((s4[13]==1) && ((price>1000)&&(price<=2000)) && (t4[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[14]=strcmp(size,"XL");
                    t4[14]=strcmp(color,"Black");
                    if((s4[14]==1) && ((price>1000)&&(price<=2000))&& (t4[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[15]=strcmp(size,"XS");
                    t4[15]=strcmp(color,"Black");
                    if((s4[15]==1) && (price>2000) && (t4[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[16]=strcmp(size,"S");
                    t4[16]=strcmp(color,"Black");
                    if((s4[16]==1) && (price>2000) && (t4[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[17]=strcmp(size,"M");
                    t4[17]=strcmp(color,"Black");
                    if((s4[17]==1) && (price>2000) && (t4[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[18]=strcmp(size,"L");
                    t4[18]=strcmp(color,"Black");
                    if((s4[18]==1) && (price>2000) && (t4[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[19]=strcmp(size,"XL");
                    t4[19]=strcmp(color,"Black");
                    if((s4[19]==1) && (price>2000) && (t4[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s4[20]=strcmp(size,"XS");
                    t4[20]=strcmp(color,"Blue");
                    if((s4[20]==1) && (price<=500) && (t4[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[21]=strcmp(size,"S");
                    t4[21]=strcmp(color,"Blue");
                    if((s4[21]==1) && (price<=500) && (t4[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[22]=strcmp(size,"M");
                    t4[22]=strcmp(color,"Blue");
                    if((s4[22]==1) && (price<=500) && (t4[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[23]=strcmp(size,"L");
                    t4[23]=strcmp(color,"Blue");
                    if((s4[23]==1) && (price<=500) && (t4[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[24]=strcmp(size,"XL");
                    t4[24]=strcmp(color,"Blue");
                    if((s4[24]==1) && (price<=500) && (t4[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s4[25]=strcmp(size,"XS");
                    t4[25]=strcmp(color,"Blue");
                    if((s4[25]==1) && ((price>500)&&(price<=1000)) && (t4[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[26]=strcmp(size,"S");
                    t4[26]=strcmp(color,"Blue");
                    if((s4[26]==1) && ((price>500)&&(price<=1000)) && (t4[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[27]=strcmp(size,"M");
                    t4[27]=strcmp(color,"Blue");
                    if((s4[27]==1) && ((price>500)&&(price<=1000)) && (t4[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[28]=strcmp(size,"L");
                    t4[28]=strcmp(color,"Blue");
                    if((s4[28]==1) && ((price>500)&&(price<=1000)) && (t4[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[29]=strcmp(size,"XL");
                    t4[29]=strcmp(color,"Blue");
                    if((s4[29]==1) && ((price>500)&&(price<=1000))&& (t4[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[30]=strcmp(size,"XS");
                    t4[30]=strcmp(color,"Blue");
                    if((s4[30]==1) && ((price>1000)&&(price<=2000)) && (t4[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[31]=strcmp(size,"S");
                    t4[31]=strcmp(color,"Blue");
                    if((s4[31]==1) && ((price>1000)&&(price<=2000)) && (t4[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[32]=strcmp(size,"M");
                    t4[32]=strcmp(color,"Blue");
                    if((s4[32]==1) && ((price>1000)&&(price<=2000)) && (t4[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[33]=strcmp(size,"L");
                    t4[33]=strcmp(color,"Blue");
                    if((s4[33]==1) && ((price>1000)&&(price<=2000)) && (t4[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[34]=strcmp(size,"XL");
                    t4[34]=strcmp(color,"Blue");
                    if((s4[34]==1) && ((price>1000)&&(price<=2000))&& (t4[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[35]=strcmp(size,"XS");
                    t4[35]=strcmp(color,"Blue");
                    if((s4[35]==1) && (price>2000) && (t4[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[36]=strcmp(size,"S");
                    t4[36]=strcmp(color,"Blue");
                    if((s4[36]==1) && (price>2000) && (t4[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[37]=strcmp(size,"M");
                    t4[37]=strcmp(color,"Blue");
                    if((s4[37]==1) && (price>2000) && (t4[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[38]=strcmp(size,"L");
                    t4[38]=strcmp(color,"Blue");
                    if((s4[38]==1) && (price>2000) && (t4[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[39]=strcmp(size,"XL");
                    t4[39]=strcmp(color,"Blue");
                    if((s4[39]==1) && (price>2000) && (t4[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[40]=strcmp(size,"XS");
                    t4[40]=strcmp(color,"Red");
                    if((s4[40]==1) && (price<=500) && (t4[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[41]=strcmp(size,"S");
                    t4[41]=strcmp(color,"Red");
                    if((s4[41]==1) && (price<=500) && (t4[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[42]=strcmp(size,"M");
                    t4[42]=strcmp(color,"Red");
                    if((s4[42]==1) && (price<=500) && (t4[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[43]=strcmp(size,"L");
                    t4[43]=strcmp(color,"Red");
                    if((s4[43]==1) && (price<=500) && (t4[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[44]=strcmp(size,"XL");
                    t4[44]=strcmp(color,"Red");
                    if((s4[44]==1) && (price<=500) && (t4[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s4[45]=strcmp(size,"XS");
                    t4[45]=strcmp(color,"Red");
                    if((s4[45]==1) && ((price>500)&&(price<=1000)) && (t4[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[46]=strcmp(size,"S");
                    t4[46]=strcmp(color,"Red");
                    if((s4[46]==1) && ((price>500)&&(price<=1000)) && (t4[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[47]=strcmp(size,"M");
                    t4[47]=strcmp(color,"Red");
                    if((s4[47]==1) && ((price>500)&&(price<=1000)) && (t4[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[48]=strcmp(size,"L");
                    t4[48]=strcmp(color,"Red");
                    if((s4[48]==1) && ((price>500)&&(price<=1000)) && (t4[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[49]=strcmp(size,"XL");
                    t4[49]=strcmp(color,"Red");
                    if((s4[49]==1) && ((price>500)&&(price<=1000))&& (t4[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[50]=strcmp(size,"XS");
                    t4[50]=strcmp(color,"Red");
                    if((s4[50]==1) && ((price>1000)&&(price<=2000)) && (t4[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[51]=strcmp(size,"S");
                    t4[51]=strcmp(color,"Red");
                    if((s4[51]==1) && ((price>1000)&&(price<=2000)) && (t4[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[52]=strcmp(size,"M");
                    t4[52]=strcmp(color,"Red");
                    if((s4[52]==1) && ((price>1000)&&(price<=2000)) && (t4[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[53]=strcmp(size,"L");
                    t4[53]=strcmp(color,"Red");
                    if((s4[53]==1) && ((price>1000)&&(price<=2000)) && (t4[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[54]=strcmp(size,"XL");
                    t4[54]=strcmp(color,"Red");
                    if((s4[54]==1) && ((price>1000)&&(price<=2000))&& (t4[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[55]=strcmp(size,"XS");
                    t4[55]=strcmp(color,"Red");
                    if((s4[55]==1) && (price>2000) && (t4[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[56]=strcmp(size,"S");
                    t4[56]=strcmp(color,"Red");
                    if((s4[56]==1) && (price>2000) && (t4[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[57]=strcmp(size,"M");
                    t4[57]=strcmp(color,"Red");
                    if((s4[57]==1) && (price>2000) && (t4[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[58]=strcmp(size,"L");
                    t4[58]=strcmp(color,"Red");
                    if((s4[58]==1) && (price>2000) && (t4[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[59]=strcmp(size,"XL");
                    t4[59]=strcmp(color,"Black");
                    if((s4[59]==1) && (price>2000) && (t4[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s4[60]=strcmp(size,"XS");
                    
                    if((s4[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[61]=strcmp(size,"S");
                    
                    if((s4[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[62]=strcmp(size,"M");
                    
                    if((s4[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[63]=strcmp(size,"L");
                    
                    if((s4[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[64]=strcmp(size,"XL");
                    
                    if((s4[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s4[65]=strcmp(size,"XS");
                   
                    if((s4[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[66]=strcmp(size,"S");
                    
                    if((s4[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[67]=strcmp(size,"M");
                    
                    if((s4[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[68]=strcmp(size,"L");
                   
                    if((s4[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[69]=strcmp(size,"XL");
                    
                    if((s4[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[70]=strcmp(size,"XS");
                    
                    if((s4[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[71]=strcmp(size,"S");
                    
                    if((s4[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[72]=strcmp(size,"M");
                    
                    if((s4[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[73]=strcmp(size,"L");
                    
                    if((s4[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[74]=strcmp(size,"XL");
                    
                    if((s4[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[75]=strcmp(size,"XS");
                    
                    if((s4[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[76]=strcmp(size,"S");
                    
                    if((s4[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s4[77]=strcmp(size,"M");
                    
                    if((s4[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s4[78]=strcmp(size,"L");
                    
                    if((s4[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s4[79]=strcmp(size,"XL");
                    
                    if((s4[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     break;
        case 5:   int s5[100],t5[60];
                    s5[0]=strcmp(size,"XS");
                    t5[0]=strcmp(color,"Black");
                    if((s5[0]==1) && (price<=500) && (t5[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[1]=strcmp(size,"S");
                    t5[1]=strcmp(color,"Black");
                    if((s5[1]==1) && (price<=500) && (t5[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[2]=strcmp(size,"M");
                    t5[2]=strcmp(color,"Black");
                    if((s5[2]==1) && (price<=500) && (t5[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[3]=strcmp(size,"L");
                    t5[3]=strcmp(color,"Black");
                    if((s5[3]==1) && (price<=500) && (t5[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[4]=strcmp(size,"XL");
                    t5[4]=strcmp(color,"Black");
                    if((s5[4]==1) && (price<=500) && (t5[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s5[5]=strcmp(size,"XS");
                    t5[5]=strcmp(color,"Black");
                    if((s5[5]==1) && ((price>500)&&(price<=1000)) && (t5[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[6]=strcmp(size,"S");
                    t5[6]=strcmp(color,"Black");
                    if((s5[6]==1) && ((price>500)&&(price<=1000)) && (t5[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[7]=strcmp(size,"M");
                    t5[7]=strcmp(color,"Black");
                    if((s5[7]==1) && ((price>500)&&(price<=1000)) && (t5[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[8]=strcmp(size,"L");
                    t5[8]=strcmp(color,"Black");
                    if((s5[8]==1) && ((price>500)&&(price<=1000)) && (t5[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[9]=strcmp(size,"XL");
                    t5[9]=strcmp(color,"Black");
                    if((s5[9]==1) && ((price>500)&&(price<=1000))&& (t5[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[10]=strcmp(size,"XS");
                    t5[10]=strcmp(color,"Black");
                    if((s5[10]==1) && ((price>1000)&&(price<=2000)) && (t5[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[11]=strcmp(size,"S");
                    t5[11]=strcmp(color,"Black");
                    if((s5[11]==1) && ((price>1000)&&(price<=2000)) && (t5[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[12]=strcmp(size,"M");
                    t5[12]=strcmp(color,"Black");
                    if((s5[12]==1) && ((price>1000)&&(price<=2000)) && (t5[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[13]=strcmp(size,"L");
                    t5[13]=strcmp(color,"Black");
                    if((s5[13]==1) && ((price>1000)&&(price<=2000)) && (t5[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[14]=strcmp(size,"XL");
                    t5[14]=strcmp(color,"Black");
                    if((s5[14]==1) && ((price>1000)&&(price<=2000))&& (t5[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[15]=strcmp(size,"XS");
                    t5[15]=strcmp(color,"Black");
                    if((s5[15]==1) && (price>2000) && (t5[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[16]=strcmp(size,"S");
                    t5[16]=strcmp(color,"Black");
                    if((s5[16]==1) && (price>2000) && (t5[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[17]=strcmp(size,"M");
                    t5[17]=strcmp(color,"Black");
                    if((s5[17]==1) && (price>2000) && (t5[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[18]=strcmp(size,"L");
                    t5[18]=strcmp(color,"Black");
                    if((s5[18]==1) && (price>2000) && (t5[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[19]=strcmp(size,"XL");
                    t5[19]=strcmp(color,"Black");
                    if((s5[19]==1) && (price>2000) && (t5[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s5[20]=strcmp(size,"XS");
                    t5[20]=strcmp(color,"Blue");
                    if((s5[20]==1) && (price<=500) && (t5[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[21]=strcmp(size,"S");
                    t5[21]=strcmp(color,"Blue");
                    if((s5[21]==1) && (price<=500) && (t5[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[22]=strcmp(size,"M");
                    t5[22]=strcmp(color,"Blue");
                    if((s5[22]==1) && (price<=500) && (t5[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[23]=strcmp(size,"L");
                    t5[23]=strcmp(color,"Blue");
                    if((s5[23]==1) && (price<=500) && (t5[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[24]=strcmp(size,"XL");
                    t5[24]=strcmp(color,"Blue");
                    if((s5[24]==1) && (price<=500) && (t5[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s5[25]=strcmp(size,"XS");
                    t5[25]=strcmp(color,"Blue");
                    if((s5[25]==1) && ((price>500)&&(price<=1000)) && (t5[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[26]=strcmp(size,"S");
                    t5[26]=strcmp(color,"Blue");
                    if((s5[26]==1) && ((price>500)&&(price<=1000)) && (t5[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[27]=strcmp(size,"M");
                    t5[27]=strcmp(color,"Blue");
                    if((s5[27]==1) && ((price>500)&&(price<=1000)) && (t5[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[28]=strcmp(size,"L");
                    t5[28]=strcmp(color,"Blue");
                    if((s5[28]==1) && ((price>500)&&(price<=1000)) && (t5[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[29]=strcmp(size,"XL");
                    t5[29]=strcmp(color,"Blue");
                    if((s5[29]==1) && ((price>500)&&(price<=1000))&& (t5[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[30]=strcmp(size,"XS");
                    t5[30]=strcmp(color,"Blue");
                    if((s5[30]==1) && ((price>1000)&&(price<=2000)) && (t5[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[31]=strcmp(size,"S");
                    t5[31]=strcmp(color,"Blue");
                    if((s5[31]==1) && ((price>1000)&&(price<=2000)) && (t5[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[32]=strcmp(size,"M");
                    t5[32]=strcmp(color,"Blue");
                    if((s5[32]==1) && ((price>1000)&&(price<=2000)) && (t5[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[33]=strcmp(size,"L");
                    t5[33]=strcmp(color,"Blue");
                    if((s5[33]==1) && ((price>1000)&&(price<=2000)) && (t5[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[34]=strcmp(size,"XL");
                    t5[34]=strcmp(color,"Blue");
                    if((s5[34]==1) && ((price>1000)&&(price<=2000))&& (t5[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[35]=strcmp(size,"XS");
                    t5[35]=strcmp(color,"Blue");
                    if((s5[35]==1) && (price>2000) && (t5[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[36]=strcmp(size,"S");
                    t5[36]=strcmp(color,"Blue");
                    if((s5[36]==1) && (price>2000) && (t5[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[37]=strcmp(size,"M");
                    t5[37]=strcmp(color,"Blue");
                    if((s5[37]==1) && (price>2000) && (t5[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[38]=strcmp(size,"L");
                    t5[38]=strcmp(color,"Blue");
                    if((s5[38]==1) && (price>2000) && (t5[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[39]=strcmp(size,"XL");
                    t5[39]=strcmp(color,"Blue");
                    if((s5[39]==1) && (price>2000) && (t5[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[40]=strcmp(size,"XS");
                    t5[40]=strcmp(color,"Red");
                    if((s5[40]==1) && (price<=500) && (t5[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[41]=strcmp(size,"S");
                    t5[41]=strcmp(color,"Red");
                    if((s5[41]==1) && (price<=500) && (t5[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[42]=strcmp(size,"M");
                    t5[42]=strcmp(color,"Red");
                    if((s5[42]==1) && (price<=500) && (t5[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[43]=strcmp(size,"L");
                    t5[43]=strcmp(color,"Red");
                    if((s5[43]==1) && (price<=500) && (t5[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[44]=strcmp(size,"XL");
                    t5[44]=strcmp(color,"Red");
                    if((s5[44]==1) && (price<=500) && (t5[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s5[45]=strcmp(size,"XS");
                    t5[45]=strcmp(color,"Red");
                    if((s5[45]==1) && ((price>500)&&(price<=1000)) && (t5[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[46]=strcmp(size,"S");
                    t5[46]=strcmp(color,"Red");
                    if((s5[46]==1) && ((price>500)&&(price<=1000)) && (t5[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[47]=strcmp(size,"M");
                    t5[47]=strcmp(color,"Red");
                    if((s5[47]==1) && ((price>500)&&(price<=1000)) && (t5[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[48]=strcmp(size,"L");
                    t5[48]=strcmp(color,"Red");
                    if((s5[48]==1) && ((price>500)&&(price<=1000)) && (t5[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[49]=strcmp(size,"XL");
                    t5[49]=strcmp(color,"Red");
                    if((s5[49]==1) && ((price>500)&&(price<=1000))&& (t5[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[50]=strcmp(size,"XS");
                    t5[50]=strcmp(color,"Red");
                    if((s5[50]==1) && ((price>1000)&&(price<=2000)) && (t5[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[51]=strcmp(size,"S");
                    t5[51]=strcmp(color,"Red");
                    if((s5[51]==1) && ((price>1000)&&(price<=2000)) && (t5[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[52]=strcmp(size,"M");
                    t5[52]=strcmp(color,"Red");
                    if((s5[52]==1) && ((price>1000)&&(price<=2000)) && (t5[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[53]=strcmp(size,"L");
                    t5[53]=strcmp(color,"Red");
                    if((s5[53]==1) && ((price>1000)&&(price<=2000)) && (t5[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[54]=strcmp(size,"XL");
                    t5[54]=strcmp(color,"Red");
                    if((s5[54]==1) && ((price>1000)&&(price<=2000))&& (t5[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[55]=strcmp(size,"XS");
                    t5[55]=strcmp(color,"Red");
                    if((s5[55]==1) && (price>2000) && (t5[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[56]=strcmp(size,"S");
                    t5[56]=strcmp(color,"Red");
                    if((s5[56]==1) && (price>2000) && (t5[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[57]=strcmp(size,"M");
                    t5[57]=strcmp(color,"Red");
                    if((s5[57]==1) && (price>2000) && (t5[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[58]=strcmp(size,"L");
                    t5[58]=strcmp(color,"Red");
                    if((s5[58]==1) && (price>2000) && (t5[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[59]=strcmp(size,"XL");
                    t5[59]=strcmp(color,"Black");
                    if((s5[59]==1) && (price>2000) && (t5[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s5[60]=strcmp(size,"XS");
                    
                    if((s5[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[61]=strcmp(size,"S");
                    
                    if((s5[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[62]=strcmp(size,"M");
                    
                    if((s5[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[63]=strcmp(size,"L");
                    
                    if((s5[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[64]=strcmp(size,"XL");
                    
                    if((s5[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s5[65]=strcmp(size,"XS");
                   
                    if((s5[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[66]=strcmp(size,"S");
                    
                    if((s5[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[67]=strcmp(size,"M");
                    
                    if((s5[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[68]=strcmp(size,"L");
                   
                    if((s5[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[69]=strcmp(size,"XL");
                    
                    if((s5[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[70]=strcmp(size,"XS");
                    
                    if((s5[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[71]=strcmp(size,"S");
                    
                    if((s5[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[72]=strcmp(size,"M");
                    
                    if((s5[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[73]=strcmp(size,"L");
                    
                    if((s5[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[74]=strcmp(size,"XL");
                    
                    if((s5[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[75]=strcmp(size,"XS");
                    
                    if((s5[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[76]=strcmp(size,"S");
                    
                    if((s5[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s5[77]=strcmp(size,"M");
                    
                    if((s5[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s5[78]=strcmp(size,"L");
                    
                    if((s5[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s5[79]=strcmp(size,"XL");
                    
                    if((s5[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     break;
            case 6: int s6[100],t6[60];
                    s6[0]=strcmp(size,"XS");
                    t6[0]=strcmp(color,"Black");
                    if((s6[0]==1) && (price<=500) && (t6[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[1]=strcmp(size,"S");
                    t6[1]=strcmp(color,"Black");
                    if((s6[1]==1) && (price<=500) && (t6[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[2]=strcmp(size,"M");
                    t6[2]=strcmp(color,"Black");
                    if((s6[2]==1) && (price<=500) && (t6[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[3]=strcmp(size,"L");
                    t6[3]=strcmp(color,"Black");
                    if((s6[3]==1) && (price<=500) && (t6[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[4]=strcmp(size,"XL");
                    t6[4]=strcmp(color,"Black");
                    if((s6[4]==1) && (price<=500) && (t6[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s6[5]=strcmp(size,"XS");
                    t6[5]=strcmp(color,"Black");
                    if((s6[5]==1) && ((price>500)&&(price<=1000)) && (t6[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[6]=strcmp(size,"S");
                    t6[6]=strcmp(color,"Black");
                    if((s6[6]==1) && ((price>500)&&(price<=1000)) && (t6[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[7]=strcmp(size,"M");
                    t6[7]=strcmp(color,"Black");
                    if((s6[7]==1) && ((price>500)&&(price<=1000)) && (t6[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[8]=strcmp(size,"L");
                    t6[8]=strcmp(color,"Black");
                    if((s6[8]==1) && ((price>500)&&(price<=1000)) && (t6[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[9]=strcmp(size,"XL");
                    t6[9]=strcmp(color,"Black");
                    if((s6[9]==1) && ((price>500)&&(price<=1000))&& (t6[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[10]=strcmp(size,"XS");
                    t6[10]=strcmp(color,"Black");
                    if((s6[10]==1) && ((price>1000)&&(price<=2000)) && (t6[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[11]=strcmp(size,"S");
                    t6[11]=strcmp(color,"Black");
                    if((s6[11]==1) && ((price>1000)&&(price<=2000)) && (t6[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[12]=strcmp(size,"M");
                    t6[12]=strcmp(color,"Black");
                    if((s6[12]==1) && ((price>1000)&&(price<=2000)) && (t6[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[13]=strcmp(size,"L");
                    t6[13]=strcmp(color,"Black");
                    if((s6[13]==1) && ((price>1000)&&(price<=2000)) && (t6[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[14]=strcmp(size,"XL");
                    t6[14]=strcmp(color,"Black");
                    if((s6[14]==1) && ((price>1000)&&(price<=2000))&& (t6[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[15]=strcmp(size,"XS");
                    t6[15]=strcmp(color,"Black");
                    if((s6[15]==1) && (price>2000) && (t6[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[16]=strcmp(size,"S");
                    t6[16]=strcmp(color,"Black");
                    if((s6[16]==1) && (price>2000) && (t6[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[17]=strcmp(size,"M");
                    t6[17]=strcmp(color,"Black");
                    if((s6[17]==1) && (price>2000) && (t6[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[18]=strcmp(size,"L");
                    t6[18]=strcmp(color,"Black");
                    if((s6[18]==1) && (price>2000) && (t6[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[19]=strcmp(size,"XL");
                    t6[19]=strcmp(color,"Black");
                    if((s6[19]==1) && (price>2000) && (t6[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s6[20]=strcmp(size,"XS");
                    t6[20]=strcmp(color,"Blue");
                    if((s6[20]==1) && (price<=500) && (t6[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[21]=strcmp(size,"S");
                    t6[21]=strcmp(color,"Blue");
                    if((s6[21]==1) && (price<=500) && (t6[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[22]=strcmp(size,"M");
                    t6[22]=strcmp(color,"Blue");
                    if((s6[22]==1) && (price<=500) && (t6[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[23]=strcmp(size,"L");
                    t6[23]=strcmp(color,"Blue");
                    if((s6[23]==1) && (price<=500) && (t6[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[24]=strcmp(size,"XL");
                    t6[24]=strcmp(color,"Blue");
                    if((s6[24]==1) && (price<=500) && (t6[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s6[25]=strcmp(size,"XS");
                    t6[25]=strcmp(color,"Blue");
                    if((s6[25]==1) && ((price>500)&&(price<=1000)) && (t6[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[26]=strcmp(size,"S");
                    t6[26]=strcmp(color,"Blue");
                    if((s6[26]==1) && ((price>500)&&(price<=1000)) && (t6[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[27]=strcmp(size,"M");
                    t6[27]=strcmp(color,"Blue");
                    if((s6[27]==1) && ((price>500)&&(price<=1000)) && (t6[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[28]=strcmp(size,"L");
                    t6[28]=strcmp(color,"Blue");
                    if((s6[28]==1) && ((price>500)&&(price<=1000)) && (t6[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[29]=strcmp(size,"XL");
                    t6[29]=strcmp(color,"Blue");
                    if((s6[29]==1) && ((price>500)&&(price<=1000))&& (t6[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[30]=strcmp(size,"XS");
                    t6[30]=strcmp(color,"Blue");
                    if((s6[30]==1) && ((price>1000)&&(price<=2000)) && (t6[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[31]=strcmp(size,"S");
                    t6[31]=strcmp(color,"Blue");
                    if((s6[31]==1) && ((price>1000)&&(price<=2000)) && (t6[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[32]=strcmp(size,"M");
                    t6[32]=strcmp(color,"Blue");
                    if((s6[32]==1) && ((price>1000)&&(price<=2000)) && (t6[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[33]=strcmp(size,"L");
                    t6[33]=strcmp(color,"Blue");
                    if((s6[33]==1) && ((price>1000)&&(price<=2000)) && (t6[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[34]=strcmp(size,"XL");
                    t6[34]=strcmp(color,"Blue");
                    if((s6[34]==1) && ((price>1000)&&(price<=2000))&& (t6[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[35]=strcmp(size,"XS");
                    t6[35]=strcmp(color,"Blue");
                    if((s6[35]==1) && (price>2000) && (t6[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[36]=strcmp(size,"S");
                    t6[36]=strcmp(color,"Blue");
                    if((s6[36]==1) && (price>2000) && (t6[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[37]=strcmp(size,"M");
                    t6[37]=strcmp(color,"Blue");
                    if((s6[37]==1) && (price>2000) && (t6[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[38]=strcmp(size,"L");
                    t6[38]=strcmp(color,"Blue");
                    if((s6[38]==1) && (price>2000) && (t6[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[39]=strcmp(size,"XL");
                    t6[39]=strcmp(color,"Blue");
                    if((s6[39]==1) && (price>2000) && (t6[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[40]=strcmp(size,"XS");
                    t6[40]=strcmp(color,"Red");
                    if((s6[40]==1) && (price<=500) && (t6[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[41]=strcmp(size,"S");
                    t6[41]=strcmp(color,"Red");
                    if((s6[41]==1) && (price<=500) && (t6[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[42]=strcmp(size,"M");
                    t6[42]=strcmp(color,"Red");
                    if((s6[42]==1) && (price<=500) && (t6[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[43]=strcmp(size,"L");
                    t6[43]=strcmp(color,"Red");
                    if((s6[43]==1) && (price<=500) && (t6[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[44]=strcmp(size,"XL");
                    t6[44]=strcmp(color,"Red");
                    if((s6[44]==1) && (price<=500) && (t6[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s6[45]=strcmp(size,"XS");
                    t6[45]=strcmp(color,"Red");
                    if((s6[45]==1) && ((price>500)&&(price<=1000)) && (t6[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[46]=strcmp(size,"S");
                    t6[46]=strcmp(color,"Red");
                    if((s6[46]==1) && ((price>500)&&(price<=1000)) && (t6[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[47]=strcmp(size,"M");
                    t6[47]=strcmp(color,"Red");
                    if((s6[47]==1) && ((price>500)&&(price<=1000)) && (t6[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[48]=strcmp(size,"L");
                    t6[48]=strcmp(color,"Red");
                    if((s6[48]==1) && ((price>500)&&(price<=1000)) && (t6[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[49]=strcmp(size,"XL");
                    t6[49]=strcmp(color,"Red");
                    if((s6[49]==1) && ((price>500)&&(price<=1000))&& (t6[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[50]=strcmp(size,"XS");
                    t6[50]=strcmp(color,"Red");
                    if((s6[50]==1) && ((price>1000)&&(price<=2000)) && (t6[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[51]=strcmp(size,"S");
                    t6[51]=strcmp(color,"Red");
                    if((s6[51]==1) && ((price>1000)&&(price<=2000)) && (t6[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[52]=strcmp(size,"M");
                    t6[52]=strcmp(color,"Red");
                    if((s6[52]==1) && ((price>1000)&&(price<=2000)) && (t6[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[53]=strcmp(size,"L");
                    t6[53]=strcmp(color,"Red");
                    if((s6[53]==1) && ((price>1000)&&(price<=2000)) && (t6[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[54]=strcmp(size,"XL");
                    t6[54]=strcmp(color,"Red");
                    if((s6[54]==1) && ((price>1000)&&(price<=2000))&& (t6[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[55]=strcmp(size,"XS");
                    t6[55]=strcmp(color,"Red");
                    if((s6[55]==1) && (price>2000) && (t6[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[56]=strcmp(size,"S");
                    t6[56]=strcmp(color,"Red");
                    if((s6[56]==1) && (price>2000) && (t6[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[57]=strcmp(size,"M");
                    t6[57]=strcmp(color,"Red");
                    if((s6[57]==1) && (price>2000) && (t6[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[58]=strcmp(size,"L");
                    t6[58]=strcmp(color,"Red");
                    if((s6[58]==1) && (price>2000) && (t6[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[59]=strcmp(size,"XL");
                    t6[59]=strcmp(color,"Black");
                    if((s6[59]==1) && (price>2000) && (t6[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s6[60]=strcmp(size,"XS");
                    
                    if((s6[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[61]=strcmp(size,"S");
                    
                    if((s6[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[62]=strcmp(size,"M");
                    
                    if((s6[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[63]=strcmp(size,"L");
                    
                    if((s6[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[64]=strcmp(size,"XL");
                    
                    if((s6[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s6[65]=strcmp(size,"XS");
                   
                    if((s6[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[66]=strcmp(size,"S");
                    
                    if((s6[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[67]=strcmp(size,"M");
                    
                    if((s6[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[68]=strcmp(size,"L");
                   
                    if((s6[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[69]=strcmp(size,"XL");
                    
                    if((s6[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[70]=strcmp(size,"XS");
                    
                    if((s6[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[71]=strcmp(size,"S");
                    
                    if((s6[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[72]=strcmp(size,"M");
                    
                    if((s6[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[73]=strcmp(size,"L");
                    
                    if((s6[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[74]=strcmp(size,"XL");
                    
                    if((s6[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[75]=strcmp(size,"XS");
                    
                    if((s6[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[76]=strcmp(size,"S");
                    
                    if((s6[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s6[77]=strcmp(size,"M");
                    
                    if((s6[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s6[78]=strcmp(size,"L");
                    
                    if((s6[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s6[79]=strcmp(size,"XL");
                    
                    if((s6[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    break;
            case 7: int s7[100],t7[60];
                    s7[0]=strcmp(size,"XS");
                    t7[0]=strcmp(color,"Black");
                    if((s7[0]==1) && (price<=500) && (t7[0]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[1]=strcmp(size,"S");
                    t7[1]=strcmp(color,"Black");
                    if((s7[1]==1) && (price<=500) && (t7[1]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[2]=strcmp(size,"M");
                    t7[2]=strcmp(color,"Black");
                    if((s7[2]==1) && (price<=500) && (t7[2]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[3]=strcmp(size,"L");
                    t7[3]=strcmp(color,"Black");
                    if((s7[3]==1) && (price<=500) && (t7[3]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[4]=strcmp(size,"XL");
                    t7[4]=strcmp(color,"Black");
                    if((s7[4]==1) && (price<=500) && (t7[4]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s7[5]=strcmp(size,"XS");
                    t7[5]=strcmp(color,"Black");
                    if((s7[5]==1) && ((price>500)&&(price<=1000)) && (t7[5]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[6]=strcmp(size,"S");
                    t7[6]=strcmp(color,"Black");
                    if((s7[6]==1) && ((price>500)&&(price<=1000)) && (t7[6]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[7]=strcmp(size,"M");
                    t7[7]=strcmp(color,"Black");
                    if((s7[7]==1) && ((price>500)&&(price<=1000)) && (t7[7]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[8]=strcmp(size,"L");
                    t7[8]=strcmp(color,"Black");
                    if((s7[8]==1) && ((price>500)&&(price<=1000)) && (t7[8]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[9]=strcmp(size,"XL");
                    t7[9]=strcmp(color,"Black");
                    if((s7[9]==1) && ((price>500)&&(price<=1000))&& (t7[9]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[10]=strcmp(size,"XS");
                    t7[10]=strcmp(color,"Black");
                    if((s7[10]==1) && ((price>1000)&&(price<=2000)) && (t7[10]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[11]=strcmp(size,"S");
                    t7[11]=strcmp(color,"Black");
                    if((s7[11]==1) && ((price>1000)&&(price<=2000)) && (t7[11]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[12]=strcmp(size,"M");
                    t7[12]=strcmp(color,"Black");
                    if((s7[12]==1) && ((price>1000)&&(price<=2000)) && (t7[12]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[13]=strcmp(size,"L");
                    t7[13]=strcmp(color,"Black");
                    if((s7[13]==1) && ((price>1000)&&(price<=2000)) && (t7[13]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[14]=strcmp(size,"XL");
                    t7[14]=strcmp(color,"Black");
                    if((s7[14]==1) && ((price>1000)&&(price<=2000))&& (t7[14]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[15]=strcmp(size,"XS");
                    t7[15]=strcmp(color,"Black");
                    if((s7[15]==1) && (price>2000) && (t7[15]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[16]=strcmp(size,"S");
                    t7[16]=strcmp(color,"Black");
                    if((s7[16]==1) && (price>2000) && (t7[16]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[17]=strcmp(size,"M");
                    t7[17]=strcmp(color,"Black");
                    if((s7[17]==1) && (price>2000) && (t7[17]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[18]=strcmp(size,"L");
                    t7[18]=strcmp(color,"Black");
                    if((s7[18]==1) && (price>2000) && (t7[18]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[19]=strcmp(size,"XL");
                    t7[19]=strcmp(color,"Black");
                    if((s7[19]==1) && (price>2000) && (t7[19]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s7[20]=strcmp(size,"XS");
                    t7[20]=strcmp(color,"Blue");
                    if((s7[20]==1) && (price<=500) && (t7[20]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[21]=strcmp(size,"S");
                    t7[21]=strcmp(color,"Blue");
                    if((s7[21]==1) && (price<=500) && (t7[21]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[22]=strcmp(size,"M");
                    t7[22]=strcmp(color,"Blue");
                    if((s7[22]==1) && (price<=500) && (t7[22]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[23]=strcmp(size,"L");
                    t7[23]=strcmp(color,"Blue");
                    if((s7[23]==1) && (price<=500) && (t7[23]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[24]=strcmp(size,"XL");
                    t7[24]=strcmp(color,"Blue");
                    if((s7[24]==1) && (price<=500) && (t7[24]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s7[25]=strcmp(size,"XS");
                    t7[25]=strcmp(color,"Blue");
                    if((s7[25]==1) && ((price>500)&&(price<=1000)) && (t7[25]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[26]=strcmp(size,"S");
                    t7[26]=strcmp(color,"Blue");
                    if((s7[26]==1) && ((price>500)&&(price<=1000)) && (t7[26]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[27]=strcmp(size,"M");
                    t7[27]=strcmp(color,"Blue");
                    if((s7[27]==1) && ((price>500)&&(price<=1000)) && (t7[27]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[28]=strcmp(size,"L");
                    t7[28]=strcmp(color,"Blue");
                    if((s7[28]==1) && ((price>500)&&(price<=1000)) && (t7[28]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[29]=strcmp(size,"XL");
                    t7[29]=strcmp(color,"Blue");
                    if((s7[29]==1) && ((price>500)&&(price<=1000))&& (t7[29]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[30]=strcmp(size,"XS");
                    t7[30]=strcmp(color,"Blue");
                    if((s7[30]==1) && ((price>1000)&&(price<=2000)) && (t7[30]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[31]=strcmp(size,"S");
                    t7[31]=strcmp(color,"Blue");
                    if((s7[31]==1) && ((price>1000)&&(price<=2000)) && (t7[31]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[32]=strcmp(size,"M");
                    t7[32]=strcmp(color,"Blue");
                    if((s7[32]==1) && ((price>1000)&&(price<=2000)) && (t7[32]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[33]=strcmp(size,"L");
                    t7[33]=strcmp(color,"Blue");
                    if((s7[33]==1) && ((price>1000)&&(price<=2000)) && (t7[33]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[34]=strcmp(size,"XL");
                    t7[34]=strcmp(color,"Blue");
                    if((s7[34]==1) && ((price>1000)&&(price<=2000))&& (t7[34]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[35]=strcmp(size,"XS");
                    t7[35]=strcmp(color,"Blue");
                    if((s7[35]==1) && (price>2000) && (t7[35]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[36]=strcmp(size,"S");
                    t7[36]=strcmp(color,"Blue");
                    if((s7[36]==1) && (price>2000) && (t7[36]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[37]=strcmp(size,"M");
                    t7[37]=strcmp(color,"Blue");
                    if((s7[37]==1) && (price>2000) && (t7[37]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[38]=strcmp(size,"L");
                    t7[38]=strcmp(color,"Blue");
                    if((s7[38]==1) && (price>2000) && (t7[38]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[39]=strcmp(size,"XL");
                    t7[39]=strcmp(color,"Blue");
                    if((s7[39]==1) && (price>2000) && (t7[39]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[40]=strcmp(size,"XS");
                    t7[40]=strcmp(color,"Red");
                    if((s7[40]==1) && (price<=500) && (t7[40]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[41]=strcmp(size,"S");
                    t7[41]=strcmp(color,"Red");
                    if((s7[41]==1) && (price<=500) && (t7[41]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[42]=strcmp(size,"M");
                    t7[42]=strcmp(color,"Red");
                    if((s7[42]==1) && (price<=500) && (t7[42]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[43]=strcmp(size,"L");
                    t7[43]=strcmp(color,"Red");
                    if((s7[43]==1) && (price<=500) && (t7[43]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[44]=strcmp(size,"XL");
                    t7[44]=strcmp(color,"Red");
                    if((s7[44]==1) && (price<=500) && (t7[44]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s7[45]=strcmp(size,"XS");
                    t7[45]=strcmp(color,"Red");
                    if((s7[45]==1) && ((price>500)&&(price<=1000)) && (t7[45]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[46]=strcmp(size,"S");
                    t7[46]=strcmp(color,"Red");
                    if((s7[46]==1) && ((price>500)&&(price<=1000)) && (t7[46]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[47]=strcmp(size,"M");
                    t7[47]=strcmp(color,"Red");
                    if((s7[47]==1) && ((price>500)&&(price<=1000)) && (t7[47]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[48]=strcmp(size,"L");
                    t7[48]=strcmp(color,"Red");
                    if((s7[48]==1) && ((price>500)&&(price<=1000)) && (t7[48]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[49]=strcmp(size,"XL");
                    t7[49]=strcmp(color,"Red");
                    if((s7[49]==1) && ((price>500)&&(price<=1000))&& (t7[49]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[50]=strcmp(size,"XS");
                    t7[50]=strcmp(color,"Red");
                    if((s7[50]==1) && ((price>1000)&&(price<=2000)) && (t7[50]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[51]=strcmp(size,"S");
                    t7[51]=strcmp(color,"Red");
                    if((s7[51]==1) && ((price>1000)&&(price<=2000)) && (t7[51]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[52]=strcmp(size,"M");
                    t7[52]=strcmp(color,"Red");
                    if((s7[52]==1) && ((price>1000)&&(price<=2000)) && (t7[52]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[53]=strcmp(size,"L");
                    t7[53]=strcmp(color,"Red");
                    if((s7[53]==1) && ((price>1000)&&(price<=2000)) && (t7[53]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[54]=strcmp(size,"XL");
                    t7[54]=strcmp(color,"Red");
                    if((s7[54]==1) && ((price>1000)&&(price<=2000))&& (t7[54]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[55]=strcmp(size,"XS");
                    t7[55]=strcmp(color,"Red");
                    if((s7[55]==1) && (price>2000) && (t7[55]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[56]=strcmp(size,"S");
                    t7[56]=strcmp(color,"Red");
                    if((s7[56]==1) && (price>2000) && (t7[56]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[57]=strcmp(size,"M");
                    t7[57]=strcmp(color,"Red");
                    if((s7[57]==1) && (price>2000) && (t7[57]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[58]=strcmp(size,"L");
                    t7[58]=strcmp(color,"Red");
                    if((s7[58]==1) && (price>2000) && (t7[58]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[59]=strcmp(size,"XL");
                    t7[59]=strcmp(color,"Black");
                    if((s7[59]==1) && (price>2000) && (t7[59]==1))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                      s7[60]=strcmp(size,"XS");
                    
                    if((s7[60]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[61]=strcmp(size,"S");
                    
                    if((s7[61]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[62]=strcmp(size,"M");
                    
                    if((s7[62]==1) && (price<=500))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[63]=strcmp(size,"L");
                    
                    if((s7[63]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[64]=strcmp(size,"XL");
                    
                    if((s7[64]==1) && (price<=500) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     s7[65]=strcmp(size,"XS");
                   
                    if((s7[65]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[66]=strcmp(size,"S");
                    
                    if((s7[66]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[67]=strcmp(size,"M");
                    
                    if((s7[67]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[68]=strcmp(size,"L");
                   
                    if((s7[68]==1) && ((price>500)&&(price<=1000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[69]=strcmp(size,"XL");
                    
                    if((s7[69]==1) && ((price>500)&&(price<=1000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[70]=strcmp(size,"XS");
                    
                    if((s7[70]==1) && ((price>1000)&&(price<=2000)) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[71]=strcmp(size,"S");
                    
                    if((s7[71]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[72]=strcmp(size,"M");
                    
                    if((s7[72]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[73]=strcmp(size,"L");
                    
                    if((s7[73]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[74]=strcmp(size,"XL");
                    
                    if((s7[74]==1) && ((price>1000)&&(price<=2000)))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[75]=strcmp(size,"XS");
                    
                    if((s7[75]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[76]=strcmp(size,"S");
                    
                    if((s7[76]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }   
                    s7[77]=strcmp(size,"M");
                    
                    if((s7[77]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     } 
                    s7[78]=strcmp(size,"L");
                    
                    if((s7[78]==1) && (price>2000))
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                    s7[79]=strcmp(size,"XL");
                    
                    if((s7[79]==1) && (price>2000) )
                    {
                        cout<<"Hyperlinks of top options"<<endl;
                        cout<<"Pls refer to the following docs file "<<endl;
                        cout<<"https://docs.google.com/document/d/1locH8xI-nI9uGtcMsOO50FYqpbS4AwYuG3fVfemQ7dI/edit"<<endl;
                     }
                     break;
            default: cout<<"Wrong choice"<<endl;
                     }

}
