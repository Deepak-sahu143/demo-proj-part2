import React from "react";

export default function About2({ handleCloseModel, handleOfferAccept }) {
  return (
    <div className="model" onClick={handleOfferAccept}>
      <div className="model-content">
        <button onClick={handleCloseModel} className="close-btn">
          X
        </button>

        <div className="content">
          click the button below to accept our amazing offer
        </div>
        <button onClick={handleOfferAccept} className="accept-btn">
          Accept Offer
        </button>
      </div>
    </div>
  );
}
