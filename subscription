#include <iostream>
#include <string>

class Subscription {
private:
    std::string status;

public:

    Subscription() : status("Inactive Subscription") {
        std::cout << status << std::endl;
    }


    Subscription(bool renewed) {
        if (renewed) {
            status = "Subscription Active";
        } else {
            status = "Subscription Expired";
        }
        std::cout << status << std::endl;
    }
};

int main() {
    
    Subscription user;

    
    bool hasRenewed = true;
    Subscription afterOneMonth(hasRenewed);

    return 0;
}
