import React from "react";
import ReactDOM from "react-dom/client";
import "./index.css";
import reportWebVitals from "./reportWebVitals";
import { BrowserRouter as Router, Routes, Route } from "react-router-dom";
import Team from "./pages/Team";
import App from "./pages/App";

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(
  <Router>
    <Routes>
      <Route exact path="/" component={App} />
      <Route exact path="/equipo" component={Team} />
    </Routes>
  </Router>
);
