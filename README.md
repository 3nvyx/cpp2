# cpp2 notes

Data strics

arrays | vectors 
linked lists | set

arrays 
shifting large qty; ---> dynamic arrays
main vs dynamic memory
anything created in dynamic; you can delet it

int *ptr = new int(3); ---------------> this is dynamic memory;
does not delete after funciton ends; removes the dangling ptr problem 

Random Access: 
** no random acess in linked list: 

Linked lists: linear data structure that allows the users to store data in non-contiguous memory locations.
              A linked list is defined as a collection of nodes where each node consists of two members which 
              represents its value and a next pointer which stores the address for the next node.
Class AnyList {
  public: ...
  private:...
    *first; //first == head, next == link;
    count;
};
  first block contains adress of the next block and the amount of blocks included in the linked-list
  middle blocks (nodes) contain adress of the next block and the content within the block; 
write current, not curr;

class Node :
{
public:
private: 
  Node *nextl 
  int data;
  getData(); // member functions;
  getNext();
  get
  ...
  current = current  --> getNext();.
};

node * current = first;
cout << current -> getData();
current = current -> getNext();


