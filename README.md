# embedded
Higher Digital Systems
int main(void)
{
SYSTEM Init();
SCH_Start();
while(1)
   {
   SCH_Dispatch_Task();
   }
   return 1;
   }
