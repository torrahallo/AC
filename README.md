# AC
AC is a new cryptocurrency and digital payment system  with a single administrator and robot running it.
onst char ACCoin_NAME[] = "ACCoin";

const uint64_t MONEY_SUPPLY = (uint64_t)(-1);

const unsigned EMISSION_SPEED_FACTOR = 90;

src/ACCoinConfig.h

const uint64_t DIFFICULTY_TARGET = 120;

const int P2P_DEFAULT_PORT = 17236;

const static boost::uuids::uuid ACCoin_NETWORK = { { 0xA1, 0x1A, 0xA1, 0x1A, 0xA1, 0x0A, 0xA1, 0x0A, 0xA0, 0x1A, 0xA0, 0x1A, 0xA0, 0x1A, 0xA1, 0x1A } };



const std::initializer_list<const char*> SEED_NODES = {
  "111.11.11.11:17236",
  "222.22.22.22:17236",
};



const uint64_t MINIMUM_FEE = 100000;


const size_t AcCoin_BLOCK_GRANTED_FULL_REWARD_ZONE = 20000;



const uint64_t ACCoin_PUBLIC_ADDRESS_BASE58_PREFIX = 0xe9; // addresses start with "f"



const char GENESIS_ACCoin_TX_HEX[] = "";


furiouscoind --print-genesis-tx
