# add-function-reset-draft-8
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
