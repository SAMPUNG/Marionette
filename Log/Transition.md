Select-Dropdown 

.select-dropdown {
  height: 0px;
  position: absolute;
  opacity: 0;
  transition-delay: 0s;
  transition-duration: .5s;
  visibility: hidden;
  width: 100%;
  z-index: 99;
}
.link-select:hover .select-dropdown {
  height: auto;
  opacity: 1;
  visibility: visible;
}
