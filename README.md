# Dictionary-python-to-c-
https://youtu.be/KuzO5b2pqRw?si=WZHY1J5TzKjeWkUU

#include <iostream>
#include <map>
#include <string>

int main() {
    
    std::map<std::string, std::string> DATA;
    DATA["GOAD"] = "TO PROVOKE";
    DATA["ABSURD"] = "UNREASONABLE";
    DATA["MORTAL"] = "LIABLE TO DEATH";
    DATA["GULLIBLE"] = "EASILY PERSUADED";
    DATA["CREDELOUS"] = "SHOWING TOO GREAT TO BELIEVE THINGS";
    DATA["VINDICTIVE"] = "UNREASONABLE DESIRE FOR REVENGE";
    DATA["DEPICTION"] = "REPRESENTATION IN WORDS OF SOMETHING OR SOMEONE";
    DATA["PERPETRATOR"] = "A PERSON WHO CARRIES OUT AN IMMORAL ACT";
    DATA["TRANCE"] = "HALF-CONCIOUS";
    DATA["ECCENTRIC"] = "UNCONVENTIONAL AND SLIGHTLY STRANGE";
    DATA["ZEPHYR"] = "MILD BREEZE";
    DATA["EPITOME"] = "TYPICAL EXAMPLE OF A PARTICULAR QUALITY";
    DATA["LETHARGY"] = "LACK OF ENERGY";
    DATA["PANACEA"] = "SOLUTION OR REMEDY FOR ALL PROBLEMS";
    DATA["EXTRAVAGANT"] = "LACKING RESTRAINT";
    DATA["HANKER"] = "STRONG DESIRE TO DO SOMETHING";
    DATA["PERIL"] = "SERIOUS AND IMMEDIATE DANGER";
    DATA["INDUCEMENT"] = "PERSUADES";
    DATA["LIABLE"] = "RESPONSIBLE BY LAW";
    DATA["GENUINELY"] = "TRUTHFUL";
    DATA["LUFFY"] = "CAPTAIN OF STRAW HAT PIRATES";
    DATA["ZORO"] = "SWORDSMAN";
    DATA["SANJI"] = "COOK";
    DATA["NAMI"] = "NAVIGATOR";
    DATA["ROBIN"] = "ARCHEOLOGIST";
    DATA["CHOPPER"] = "DOCTOR";
    DATA["FRANKY"] = "SHIPWRIGHT";
    DATA["BROOK"] = "MUSICIAN";
    DATA["USSOP"] = "SNIPER";
    DATA["JINBEI"] = "HELMSMAN";
    DATA["THOUSAND SUNNY"] = "SHIP";

    std::string a;
    std::cout << "Say ";
    std::cin >> a;

    
    auto it = DATA.find(a);
    if (it != DATA.end()) {
        std::cout << it->second << std::endl;
    } else {
        std::cout << "di ko alam yan pre"
        << std::endl;
    }

    return 0;
}
