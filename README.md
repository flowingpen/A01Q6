A01Q6
=====
void count(struct node*head, int n)
{
struct node*temp=head;
int count=0;
while(temp)
{
if(temp->data==n)
{
count++;
}
temp=temp->next;
}
}
