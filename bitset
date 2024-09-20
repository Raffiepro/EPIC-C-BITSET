template<int SIZE>
struct bitset
{
    unsigned char bytes[SIZE];
    
    bool operator [](int bit) {
        return (bytes[SIZE-1-(bit/8)]>>(bit%8))&1;
    }
    bool operator [](int bit) const {
        return (bytes[SIZE-1-(bit/8)]>>(bit%8))&1;
    }
};
